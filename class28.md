# Our first topic is about Configuring Django Settings: Best Practices

## What are the concers we have with managing Django Settings ?

1- Different environments; Each environment can have its own specific settings

2- Sensitive data ; we have SECRET_KEY in each Django project, also there can be DB passwords.

3-Sharing settings between team members.

4- Django settings are a Python code.

## So what practices we can follow to avoid this issues?

1- **settings_local .py**

- Extend all environment-specific settings in the settings_local.py file, which is ignored by VCS.

- Pros: Secrets not in VCS.

- Cons:

1- settings_local.py is not in VCS, so you can lose some of your Django environment settings.
2- The Django settings file is a Python code, so settings_local.py can have some non-obvious logic.
3- You need to have settings_local.example (in VCS) to share the default configurations for developers.

2- **Separate settings file for each environment**

- Pros:

- Configuration is separated from code.
- Environment parity – you have the same code for all environments.
- No inheritance in settings, and cleaner and more consistent code.
- There is a theoretical grounding for using environment variables – 12 Factors.

- Cons:

    You need to handle sharing default config between developers.

### 12 Factors recommendations

- 12 Factors is a collection of recommendations on how to build distributed web-apps 

- The collection consists of twelve parts:

- Codebase
- Dependencies
- Config
- Backing services
- Build, release, run
- Processes
- Port binding
- Concurrency
- Disposability
- Dev/prod parity
- Logs
- Admin processes

### So environment variables are the perfect place to store settings.

### As a conclusion Best practices for Django Settings

- Keep settings in environment variables.

- Write default values for production configuration (excluding secret keys and tokens)

- Don’t hardcode sensitive settings, and don’t put them in VCS.

- Split settings into groups: Django, third-party, project.

- Follow naming conventions for custom (project) settings.

# Our second topic is about How Does SSH Work?

![ssh](https://tsh.io/wp-content/uploads/2021/02/ssh-tutorial-lead_.png)

## What is SSH ?

> SSH, or Secure Shell, is a remote administration protocol that allows users to control and modify their remote servers over the Internet.

## How Does SSH Work?

- From the terminal program, type The SSH command which consists of 3 distinct parts:

`ssh {user}@{host}`

- The **SSH key** command instructs your system that you want to open an encrypted Secure Shell Connection.

- **{user}** represents the account you want to access. 
- **{host}** refers to the computer you want to access.

## There are three different encryption technologies used by SSH:

- Symmetrical encryption; is a form of encryption where a secret key is used for both encryption and decryption of a message by both the client and the host. 

- Asymmetrical encryption;  uses two separate keys for encryption and decryption. These two keys are known as the public key and the private key.

- Hashing; They generate a unique value of a fixed length for each input that shows no clear trend which can exploited.

## How Does SSH Work with These Encryption Techniques

- The way SSH works is by making use of a client-server model to allow for authentication of two remote systems and encryption of the data that passes between them.

## Authenticating the User

- The final stage before the user is granted access to the server is authenticating his/her credentials.

- These credentials securely pass through the symmetrically encrypted tunnel, so there is no chance of them being captured by a third party.

- Instead, the recommended alternative is SSH Key Pairs.
