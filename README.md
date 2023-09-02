# Sonic Anemometer Toolbox: the Imaginary Mast Approach

## Summary

This toolbox provides Matlab scripts tailored for the processing of wind turbulence data acquired from 3D sonic anemometers mounted on masts. The core functionalities encompass:
1. Tilt correction algorithm
2. Stationary test
3. Gaussian fluctuation test
4. Estimation of variance and covariance of turbulence (considering three velocity fluctuations and sonic temperature data)
5. One-point spectral analysis
6. Two-point spectral analysis (examining coherence of turbulence)

The unique approach of using an "Imaginary Mast" is showcased in this repository. This methodology has been applied in the study of atmospheric turbulence in various settings, including complex terrains [1][2] and offshore environments [3][4].

## Repository Structure

- **Functions Directory**: Houses the essential scripts and functions for data processing.
- **Data Directory**: Showcases dummy wind velocity data represented in 3D matrices for daily recordings. The matrix dimension is denoted as `[MxNxK]` where:
   - `M` - Number of sensors
   - `N` - Number of samples
   - `K` - Number of time steps
- **Matlab LiveScript**: A demonstrative document detailing the function applications, utilizing a hypothetical "Imaginary Mast" as a case study.

> **Note**: As this is the inaugural version of the repository, it may contain some bugs. Users are encouraged to provide feedback to facilitate enhancements.

## References

[1] Midjiyawa, Z., Cheynet, E., Reuder, J., Ágústsson, H., & Kvamsdal, T. (2021). Potential and challenges of wind measurements using met-masts in complex topography for bridge design: Part I–Integral flow characteristics. Journal of Wind Engineering and Industrial Aerodynamics, 211, 104584.

[2] Midjiyawa, Z., Cheynet, E., Reuder, J., Ágústsson, H., & Kvamsdal, T. (2021). Potential and challenges of wind measurements using met-masts in complex topography for bridge design: Part II–Spectral flow characteristics. Journal of Wind Engineering and Industrial Aerodynamics, 211, 104585.

[3] Putri, R. M., Cheynet, E., Obhrai, C., & Jakobsen, J. B. (2022). Turbulence in a coastal environment: the case of Vindeby. Wind Energy Science, 7(4), 1693-1710.

[4] Cheynet, E., Jakobsen, J. B., & Reuder, J. (2018). Velocity spectra and coherence estimates in the marine atmospheric boundary layer. Boundary-layer meteorology, 169(3), 429-460.

## Contributing

For suggestions, bug reports, or contributions, please initiate an issue or forward a pull request or leave a comment on Matlab File Exchange. 
