# Implementation of Self Attention Guidance in webui
https://arxiv.org/abs/2210.00939

## Additional setup requirements after installation:

### For AUTOMATIC1111 webui:
at commit 22bcc7be

run the following command in root directory stable-diffusion-webui/:
```
git apply --ignore-whitespace extensions/sd_webui_SAG/automatic1111-CFGDenoiser-and-script_callbacks-mod-for-SAG.patch
```


### ~~For vladmandic webui:~~
No longer requires patching after commit [cb465b1](https://github.com/vladmandic/automatic/commit/cb465b12ddc5e4b5f6566030021a26630b927ba6)
since required changes have been merged to upstream.


Demos:
![xyz_grid-0014-232592377.png](resources%2Fimg%2Fxyz_grid-0014-232592377.png)
![xyz_grid-0001-232592377.png](resources%2Fimg%2Fxyz_grid-0001-232592377.png)