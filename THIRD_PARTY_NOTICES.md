# Third-party software

apk-rebrand bundles the following libraries. Their licenses apply to the respective parts.

| Library | Version | License | Used for |
|---|---|---|---|
| [ARSCLib](https://github.com/REAndroid/ARSCLib) | 1.4.0 | Apache License 2.0 | Reading and writing `AndroidManifest.xml`, `resources.arsc` and the APK archive |
| [apksig](https://android.googlesource.com/platform/tools/apksig) (from Android SDK build-tools 34.0.0) | 34.0.0 | Apache License 2.0 | APK signing (v1/v2/v3) and signature verification |
| [TwelveMonkeys ImageIO](https://github.com/haraldk/TwelveMonkeys) (`imageio-webp` and its dependencies) | 3.15.3 | BSD 3-Clause | WebP decoding in the desktop tool only |

`libs/apksig-34.0.0.jar` contains only the `com.android.apksig` library classes taken from
`build-tools/34.0.0/lib/apksigner.jar`.

License texts: <https://www.apache.org/licenses/LICENSE-2.0> and
<https://github.com/haraldk/TwelveMonkeys/blob/master/LICENSE.txt>.
