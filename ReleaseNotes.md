﻿# Mile.Project.Configurations Release Notes

**Mile.Project.Configurations 1.0.1426.0**

- Initial release.
- Inherit and integrate Mile.Project.Platform from
  https://github.com/ProjectMile/Mile.Project.Windows/tree/20241012-BeforeNuGetSDK.
- Fix the condition check for Mile.Project.Platform x86.
- Add empty SDK configurations for simplifying the configurations.
- Fix the file header for Mile.Project.Platform.
- Inherit and integrate Mile.Project.Version from
  https://github.com/ProjectMile/Mile.Project.Windows/tree/20241012-BeforeNuGetSDK.
- Inherit and integrate Mile.Project.Manifest from
  https://github.com/ProjectMile/Mile.Project.Windows/tree/20241012-BeforeNuGetSDK.
- Inherit and integrate Mile.Project.Cpp from
  https://github.com/ProjectMile/Mile.Project.Windows/tree/20241012-BeforeNuGetSDK.
- Inherit and integrate Mile.Project.Wap from 
  https://github.com/ProjectMile/Mile.Project.Windows/tree/20241012-BeforeNuGetSDK.
- Inherit and integrate Mile.Project.Build from
  https://github.com/ProjectMile/Mile.Project.Windows/tree/20241012-BeforeNuGetSDK.
- Set BackgroundTaskDebugEngines to NativeOnly in Mile.Project.Wap.props.
- Introduce MileProjectOutputPath, MileProjectCppDisablePackageReferencesSupport
  and MileProjectWapDisableNativeProjectWorkarounds options.
