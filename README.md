# OMSWebMini_IS4_MembershipProvider

# Description 
Making GET request to protected WebAPI using OAuth 2.0 and OpenIdConnect protocols

# Sequence 
First of all user goes through authentication via MVC Client then authority in face of Identity Server4 gives JWT token which MVC client uses to make GET "customers" request then receive response and deserialize it

# Membership provider
Membership provider(user credentials' storage) is ASP .NET Identity

## First step - authentication
![](https://github.com/Allaev1/OMSWebMini_IS4_MembershipProvider/blob/master/images/IS%204.jpg?raw=true)

## Second step - Log in occured
![](https://github.com/Allaev1/OMSWebMini_IS4_MembershipProvider/blob/master/images/IS%204_1.jpg?raw=true)

## Third step - Do request to protected WebAPI
![](https://github.com/Allaev1/OMSWebMini_IS4_MembershipProvider/blob/master/images/IS%204_2.jpg?raw=true)

## Fourth step - Log out
![](https://github.com/Allaev1/OMSWebMini_IS4_MembershipProvider/blob/master/images/IS%204_3.jpg?raw=true)
