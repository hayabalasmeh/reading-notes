# Our Topic is about Permissions in Django REST Framework

![permissions](https://i.ytimg.com/vi/eBsc65jTKvw/maxresdefault.jpg)

## For What we use the Permission?

- Permissions are used to grant or deny access for different classes of users to different parts of the API.

## How permissions are determined ?

- Before running the main body of the view each permission in the list is checked. 

- If any permission check fails an **exceptions.PermissionDenied** or **exceptions.NotAuthenticated** exception will be raised, and the main body of the view will not run.

## Object level permissions

### What do we mean by this ?

- Object level permissions are used to determine if a user should be allowed to act on a particular object, which will typically be a model instance.

- Object level permissions are run by REST framework's generic views when .**get_object()** is called. 

- As with view level permissions, an **exceptions.PermissionDenied** exception will be raised if the user is not allowed to act on the given object.

### Limitations of object level permissions

- For performance reasons the generic views will not automatically apply object level permissions to each instance in a queryset when returning a list of objects.

## Setting the permission policy

- There are multiple ways for doing this setting;

1- The default permission policy may be set globally, using the DEFAULT_PERMISSION_CLASSES setting.

2- You can also set the authentication policy on a per-view, or per-viewset basis, using the APIView class-based views

## API Reference

### AllowAny

- The AllowAny permission class will allow unrestricted access, regardless of if the request was authenticated or unauthenticated.

### IsAuthenticated

- The IsAuthenticated permission class will deny permission to any unauthenticated user, and allow permission otherwise.


### IsAdminUser

- The IsAdminUser permission class will deny permission to any user, unless user.is_staff is True in which case permission will be allowed.


### IsAuthenticatedOrReadOnly

- The IsAuthenticatedOrReadOnly will allow authenticated users to perform any request. 

- Requests for unauthorised users will only be permitted if the request method is one of the "safe" methods; GET, HEAD or OPTIONS.


### DjangoModelPermissions

- Authorization will only be granted if the user is authenticated and has the relevant model permissions assigned.


### DjangoModelPermissionsOrAnonReadOnly

- Similar to DjangoModelPermissions, but also allows unauthenticated users to have read-only access to the API.


### DjangoObjectPermissions

- Authorization will only be granted if the user is authenticated and has the relevant per-object permissions and relevant model permissions assigned.


### Overview of access restriction methods

- REST framework offers three different methods to customize access restrictions on a case-by-case basis;

    - **queryset/get_queryset()**: Limits the general visibility of existing objects from the database. 

    - **permission_classes/get_permissions():** General permission checks based on the current action, request and targeted object. 

    - **serializer_class/get_serializer()**: Instance level restrictions that apply to all objects on input and output. 
