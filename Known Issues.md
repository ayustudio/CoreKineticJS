# Known Issues

As of version 1.0.0, the following minor issues are known in CoreKineticJS:

1. Type safety warnings in ScrollAnimation plugin:
   - The `updateElement` method in `src/plugins/ScrollAnimation.ts` uses `any` type when setting style properties. This may lead to less strict type checking for style properties.

2. Type safety warning in LottieAnimation plugin:
   - The `load` method in `src/plugins/LottieAnimation.ts` uses `any` type for the `animationData` parameter. This may provide less type information for users of the library when working with Lottie animations.

3. Limited browser compatibility testing:
   - While efforts have been made to ensure broad compatibility, extensive testing across all browser versions has not yet been completed.

4. Performance benchmarking:
   - Comprehensive performance benchmarking across various devices and scenarios is still in progress.

5. WebGL fallback:
   - In scenarios where WebGL is not supported, the fallback mechanism may not provide identical visual results in all cases.

These issues do not significantly impact the functionality of the library and will be addressed in future updates. If you encounter any problems related to these issues, please report them on our GitHub issues page.
