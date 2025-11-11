# Astro Image Format Issue

## Description

After building the project, check the `dist/_astro` directory. You will notice that images are automatically converted to WebP format.

While this can be prevented by specifying the `format` property on each Image component, it would be inconvenient to apply this to all Image components individually. Therefore, it would be desirable to set this behavior globally in `astro.config`.

## Steps to Reproduce

1. Build the project
2. Check the `dist/_astro` directory
3. Observe that images have been converted to WebP format

## Expected Behavior

There should be a way to configure the default image format globally in the Astro configuration file, preventing automatic conversion to WebP without having to specify the format on each individual Image component.
