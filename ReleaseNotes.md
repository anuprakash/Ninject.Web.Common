Version 3.2.3
---------------
- Added Owin 3.0 support

Version 3.2.2
---------------
- Fixed that InRequestScoped objects were not released immediatly anymore due to missing call registration in GlobalKernelRegistration.

Version 3.2.1
---------------
- Added WebCommonNinjectModule that contains the bindings that are shared among all web extesnions to support multiple of them in one application. 

Version 3.2.0.0
---------------
- Added OWIN support.

Version 3.0.0.0
---------------
- Inintial release: This package is the base for all web extensions.
- Changed: OnePerRequestModule has been renamed to OnePerRequestHttpModule 
