# minimap2 meson
How to use minimap2 in your meson project?
Use one of the following wrapdb entries and this meson dependency:

    my_minimap2_dep = dependency('minimap2', fallback : ['minimap2', 'mm2_dep'])

## Version 2.5

    [wrap-file]
    directory=minimap2-2.5

    source_url=https://github.com/lh3/minimap2/archive/v2.5.zip
    source_filename = minimap2-2.5.zip
    source_hash = 6947a74c896e91a459cbbf7693f650a068bddc77995681aee17708317870bd9a

    patch_url = https://github.com/armintoepfer/minimap2-meson/releases/download/zero/minimap2-2.5-wrap.zip
    patch_filename = minimap2-v2.5.zip
    patch_hash = 7fee591d53375cdf44b79c32e96c8fb46ed98d617b9a5d900c87fb7922be0e38

