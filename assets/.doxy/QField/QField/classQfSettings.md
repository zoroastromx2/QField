

# Class QfSettings



[**ClassList**](annotated.md) **>** [**QfSettings**](classQfSettings.md)








Inherits the following classes: Page,  QSettings


























## Public Properties

| Type | Name |
| ---: | :--- |
| property alias | [**autoOpenFormSingleIdentify**](classQfSettings.md#property-autoopenformsingleidentify)  <br> |
| property alias | [**autoSave**](classQfSettings.md#property-autosave)  <br> |
| property alias | [**autoZoomToIdentifiedFeature**](classQfSettings.md#property-autozoomtoidentifiedfeature)  <br> |
| property alias | [**currentPanel**](classQfSettings.md#property-currentpanel)  <br> |
| property alias | [**digitizingVolumeKeys**](classQfSettings.md#property-digitizingvolumekeys)  <br> |
| property alias | [**enableInfoCollection**](classQfSettings.md#property-enableinfocollection)  <br> |
| property alias | [**enableMapRotation**](classQfSettings.md#property-enablemaprotation)  <br> |
| property alias | [**fingerTapDigitizing**](classQfSettings.md#property-fingertapdigitizing)  <br> |
| property alias | [**fullScreenIdentifyView**](classQfSettings.md#property-fullscreenidentifyview)  <br> |
| property alias | [**locatorKeepScale**](classQfSettings.md#property-locatorkeepscale)  <br> |
| property alias | [**mouseAsTouchScreen**](classQfSettings.md#property-mouseastouchscreen)  <br> |
| property alias | [**nativeCamera2**](classQfSettings.md#property-nativecamera2)  <br> |
| property alias | [**numericalDigitizingInformation**](classQfSettings.md#property-numericaldigitizinginformation)  <br> |
| property alias | [**previewJobsEnabled**](classQfSettings.md#property-previewjobsenabled)  <br> |
| property bool | [**proxyEnabled**](classQfSettings.md#property-proxyenabled)  <br> |
| property string | [**proxyExcludedUrls**](classQfSettings.md#property-proxyexcludedurls)  <br> |
| property string | [**proxyHost**](classQfSettings.md#property-proxyhost)  <br> |
| property string | [**proxyPassword**](classQfSettings.md#property-proxypassword)  <br> |
| property int | [**proxyPort**](classQfSettings.md#property-proxyport)  <br> |
| property bool | [**proxySettingsLoaded**](classQfSettings.md#property-proxysettingsloaded)  <br> |
| property string | [**proxyType**](classQfSettings.md#property-proxytype)  <br> |
| property string | [**proxyUser**](classQfSettings.md#property-proxyuser)  <br> |
| property alias | [**quality**](classQfSettings.md#property-quality)  <br> |
| property alias | [**showBookmarks**](classQfSettings.md#property-showbookmarks)  <br> |
| property alias | [**showScaleBar**](classQfSettings.md#property-showscalebar)  <br> |
| property alias | [**showZoomControls**](classQfSettings.md#property-showzoomcontrols)  <br> |
| property alias | [**snapToCommonAngleDegrees**](classQfSettings.md#property-snaptocommonangledegrees)  <br> |
| property alias | [**snapToCommonAngleIsEnabled**](classQfSettings.md#property-snaptocommonangleisenabled)  <br> |
| property alias | [**snapToCommonAngleIsRelative**](classQfSettings.md#property-snaptocommonangleisrelative)  <br> |
| property alias | [**snapToCommonAngleTolerance**](classQfSettings.md#property-snaptocommonangletolerance)  <br> |




## Public Signals

| Type | Name |
| ---: | :--- |
| signal void | [**finished**](classQfSettings.md#signal-finished)  <br> |
| signal void | [**settingChanged**](classQfSettings.md#signal-settingchanged) (const QString & key) <br> |




## Public Functions

| Type | Name |
| ---: | :--- |
|   | [**QfSettings**](#function-qfsettings) (QObject \* parent=nullptr) <br> |
|  void | [**applyProxySettings**](#function-applyproxysettings) () <br> |
|  Q\_INVOKABLE void | [**remove**](#function-remove) (const QString & key) <br> |
|  void | [**reset**](#function-reset) () <br> |
|  Q\_INVOKABLE void | [**setValue**](#function-setvalue) (const QString & key, const QVariant & value) <br> |
|  Q\_INVOKABLE void | [**sync**](#function-sync) () <br> |
|  Q\_INVOKABLE QVariant | [**value**](#function-value) (const QString & key, const QVariant & defaultValue) <br> |
|  Q\_INVOKABLE bool | [**valueBool**](#function-valuebool) (const QString & key, bool defaultValue) <br> |
|  Q\_INVOKABLE int | [**valueInt**](#function-valueint) (const QString & key, int defaultValue) <br> |




























## Public Properties Documentation




### property autoOpenFormSingleIdentify 

```C++
alias QfSettings::autoOpenFormSingleIdentify;
```




<hr>



### property autoSave 

```C++
alias QfSettings::autoSave;
```




<hr>



### property autoZoomToIdentifiedFeature 

```C++
alias QfSettings::autoZoomToIdentifiedFeature;
```




<hr>



### property currentPanel 

```C++
alias QfSettings::currentPanel;
```




<hr>



### property digitizingVolumeKeys 

```C++
alias QfSettings::digitizingVolumeKeys;
```




<hr>



### property enableInfoCollection 

```C++
alias QfSettings::enableInfoCollection;
```




<hr>



### property enableMapRotation 

```C++
alias QfSettings::enableMapRotation;
```




<hr>



### property fingerTapDigitizing 

```C++
alias QfSettings::fingerTapDigitizing;
```




<hr>



### property fullScreenIdentifyView 

```C++
alias QfSettings::fullScreenIdentifyView;
```




<hr>



### property locatorKeepScale 

```C++
alias QfSettings::locatorKeepScale;
```




<hr>



### property mouseAsTouchScreen 

```C++
alias QfSettings::mouseAsTouchScreen;
```




<hr>



### property nativeCamera2 

```C++
alias QfSettings::nativeCamera2;
```




<hr>



### property numericalDigitizingInformation 

```C++
alias QfSettings::numericalDigitizingInformation;
```




<hr>



### property previewJobsEnabled 

```C++
alias QfSettings::previewJobsEnabled;
```




<hr>



### property proxyEnabled 

```C++
bool QfSettings::proxyEnabled;
```




<hr>



### property proxyExcludedUrls 

```C++
string QfSettings::proxyExcludedUrls;
```




<hr>



### property proxyHost 

```C++
string QfSettings::proxyHost;
```




<hr>



### property proxyPassword 

```C++
string QfSettings::proxyPassword;
```




<hr>



### property proxyPort 

```C++
int QfSettings::proxyPort;
```




<hr>



### property proxySettingsLoaded 

```C++
bool QfSettings::proxySettingsLoaded;
```




<hr>



### property proxyType 

```C++
string QfSettings::proxyType;
```




<hr>



### property proxyUser 

```C++
string QfSettings::proxyUser;
```




<hr>



### property quality 

```C++
alias QfSettings::quality;
```




<hr>



### property showBookmarks 

```C++
alias QfSettings::showBookmarks;
```




<hr>



### property showScaleBar 

```C++
alias QfSettings::showScaleBar;
```




<hr>



### property showZoomControls 

```C++
alias QfSettings::showZoomControls;
```




<hr>



### property snapToCommonAngleDegrees 

```C++
alias QfSettings::snapToCommonAngleDegrees;
```




<hr>



### property snapToCommonAngleIsEnabled 

```C++
alias QfSettings::snapToCommonAngleIsEnabled;
```




<hr>



### property snapToCommonAngleIsRelative 

```C++
alias QfSettings::snapToCommonAngleIsRelative;
```




<hr>



### property snapToCommonAngleTolerance 

```C++
alias QfSettings::snapToCommonAngleTolerance;
```




<hr>
## Public Signals Documentation




### signal finished 

```C++
void QfSettings::finished;
```




<hr>



### signal settingChanged 

```C++
void QfSettings::settingChanged;
```




<hr>
## Public Functions Documentation




### function QfSettings 

```C++
explicit QfSettings::QfSettings (
    QObject * parent=nullptr
) 
```




<hr>



### function applyProxySettings 

```C++
void QfSettings::applyProxySettings () 
```




<hr>



### function remove 

```C++
Q_INVOKABLE void QfSettings::remove (
    const QString & key
) 
```



Removes the given _key_ from settings. 


        

<hr>



### function reset 

```C++
void QfSettings::reset () 
```




<hr>



### function setValue 

```C++
Q_INVOKABLE void QfSettings::setValue (
    const QString & key,
    const QVariant & value
) 
```




<hr>



### function sync 

```C++
Q_INVOKABLE void QfSettings::sync () 
```



Writes any unsaved changes to permanent storage, and reloads the settings. 


        

<hr>



### function value 

```C++
Q_INVOKABLE QVariant QfSettings::value (
    const QString & key,
    const QVariant & defaultValue
) 
```




<hr>



### function valueBool 

```C++
Q_INVOKABLE bool QfSettings::valueBool (
    const QString & key,
    bool defaultValue
) 
```



Properly evaluates the returned value to be boolean. If the normal value() is used instead, a string "true" or "false" will be returned which will be evaluated to true either way by JS. 


        

<hr>



### function valueInt 

```C++
Q_INVOKABLE int QfSettings::valueInt (
    const QString & key,
    int defaultValue
) 
```



Properly evaluates the returned value to be int. If the normal value() is used instead, a string "1" or "-456" will be returned. 


        

<hr>

------------------------------
The documentation for this class was generated from the following file `src/app/qml/QfSettings.qml`

