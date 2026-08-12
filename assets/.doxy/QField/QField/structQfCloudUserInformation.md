

# Struct QfCloudUserInformation



[**ClassList**](annotated.md) **>** [**QfCloudUserInformation**](structQfCloudUserInformation.md)


































## Public Properties

| Type | Name |
| ---: | :--- |
| property QString | [**email**](structQfCloudUserInformation.md#property-email)  <br> |
| property QString | [**username**](structQfCloudUserInformation.md#property-username)  <br> |








## Public Functions

| Type | Name |
| ---: | :--- |
|   | [**QfCloudUserInformation**](#function-qfclouduserinformation-13) () = default<br> |
|   | [**QfCloudUserInformation**](#function-qfclouduserinformation-23) (const QString & username, const QString & email) <br> |
|   | [**QfCloudUserInformation**](#function-qfclouduserinformation-33) (const QJsonObject cloudUserInformation) <br> |
|  bool | [**isEmpty**](#function-isempty) () const<br> |
|  bool | [**operator==**](#function-operator) (const [**QfCloudUserInformation**](structQfCloudUserInformation.md) & other) const<br> |
|  QJsonObject | [**toJson**](#function-tojson) () const<br> |




























## Public Properties Documentation




### property email 

```C++
QString QfCloudUserInformation::email;
```




<hr>



### property username 

```C++
QString QfCloudUserInformation::username;
```




<hr>
## Public Functions Documentation




### function QfCloudUserInformation [1/3]

```C++
QfCloudUserInformation::QfCloudUserInformation () = default
```




<hr>



### function QfCloudUserInformation [2/3]

```C++
inline QfCloudUserInformation::QfCloudUserInformation (
    const QString & username,
    const QString & email
) 
```




<hr>



### function QfCloudUserInformation [3/3]

```C++
inline explicit QfCloudUserInformation::QfCloudUserInformation (
    const QJsonObject cloudUserInformation
) 
```




<hr>



### function isEmpty 

```C++
inline bool QfCloudUserInformation::isEmpty () const
```




<hr>



### function operator== 

```C++
inline bool QfCloudUserInformation::operator== (
    const QfCloudUserInformation & other
) const
```




<hr>



### function toJson 

```C++
inline QJsonObject QfCloudUserInformation::toJson () const
```




<hr>

------------------------------
The documentation for this class was generated from the following file `src/core/utils/qfcloudutils.h`

