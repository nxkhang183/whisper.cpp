# whisper.cpp (Dubby addon builds)

Release host for the prebuilt whisper.cpp Node addons (CPU, Core ML/Metal, CUDA, Vulkan) that [Dubby](https://github.com/nxkhang183/Dubby) downloads at runtime. The app reads the `latest` release (`addon-versions.json` plus one archive per platform/backend).

The artifacts were built by [buxuku/whisper.cpp](https://github.com/buxuku/whisper.cpp) (builder branch), itself based on [ggml-org/whisper.cpp](https://github.com/ggml-org/whisper.cpp). MIT licensed; see [LICENSE](LICENSE).
