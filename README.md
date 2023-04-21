# Implementation of Self Attention Guidance in webui
https://arxiv.org/abs/2210.00939

## Additional setup requirements after installation:

### For AUTOMATIC1111 webui:
at commit 22bcc7be

run the following command in root directory stable-diffusion-webui/:
```
git apply --ignore-whitespace extensions/sd_webui_SAG/automatic1111-CFGDenoiser-and-script_callbacks-mod-for-SAG.patch
```


### For vladmandic webui:
at commit 7c684a8b

run the following command in root directory automatic/
```
git apply --ignore-whitespace extensions/sd_webui_SAG/vladmandic-CFGDenoiser-and-script_callbacks-mod-for-SAG.patch
```


Demos with stealth pnginfo:
![xyz_grid-0014-232592377.png](resources%2Fimg%2Fxyz_grid-0014-232592377.png)
![xyz_grid-0001-232592377.png](resources%2Fimg%2Fxyz_grid-0001-232592377.png)