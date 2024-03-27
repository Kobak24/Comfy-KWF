----> Some workflows use the old Ipa Adapter Plus repo, use git reset --hard 6a411dc to revert to the working one. Workflows with the new IPA Adapter have that stated in the Name (IPA-V2, all HERO WF have been updated, just double check or play with ipadapter strength if something's off)

NODE_TESTING folder contains just simple workflows for testing various nodes, the hint is in the name

EXPLORATIONS contains more complex workflows for t2v or v2v generation using various approaches, which might not all be clear and clean

HERO_WF contains cleaned workflows with notes, which I've fully developed and usually use.

IMG_TIPS contains screenshots about workflows or node usage found here and there

RESOURCERS contains some custom things I made like DW poses, initial videos from C4D and animated masks, simple stuff but fun indeed


Here are some random info about my setup:
** Platform: Windows
** Python version: 3.11.6 (tags/v3.11.6:8b6ee5b, Oct  2 2023, 14:57:12) [MSC v.1935 64 bit (AMD64)]
Total VRAM 16376 MB, total RAM 65271 MB
xformers version: 0.0.23.post1
Set vram state to: NORMAL_VRAM
Device: cuda:0 NVIDIA GeForce RTX 4090 Laptop GPU : cudaMallocAsync
VAE dtype: torch.bfloat16
Using xformers cross attention
torch version---------------------- 2.1.2+cu121
DWPose: Onnxruntime with acceleration providers detected

Installed nodes:
   ComfyUI_cspnodes
   ComfyUI-RAVE
   ComfyUi_NNLatentUpscale
   style_aligned_comfy
   ComfyUI-deepcache
   ComfyUI-Logic
   ComfyUI_essentials
   ComfyUI_toyxyz_test_nodes
   ComfyUI_Noise
   ComfyUI-SDXL-EmptyLatentImage
   mikey_nodes
   sdxl-recommended-res-calc
   StableZero123-comfyui
   ComfyUI-LightGlue
   sd-dynamic-thresholding
   ComfyUI_TiledKSampler
   ComfyUI_IPAdapter_plus
   IPAdapter-ComfyUI
   comfyui-various
   ComfyUI-Llama
   deforum-comfy-nodes
   ComfyUI-KJNodes
   ComfyUI_FizzNodes
   ComfyUI-Marigold
   ComfyUI-Video-Matting
   ComfyUI-moondream
   ComfyUI_Dave_CustomNode
   steerable-motion
   ComfyUI_UltimateSDUpscale
   ComfyMath
   ComfyUI-SUPIR
   ComfyUI-MotionCtrl
   ComfyUI-Custom-Scripts
   ComfyUI-Advanced-ControlNet
   comfyui-prompt-control
   comfyui-browser
   ComfyUI-Inspire-Pack
   ComfyUI-VideoHelperSuite
   ComfyUI-PixelArt-Detector
   ComfyUI-AnimateAnyone-Evolved
   ComfyUI-Whisper
   ComfyUI-Frame-Interpolation
   rgthree-comfy
   ComfyUI_Comfyroll_CustomNodes
   ComfyUI-ADMotionDirector
   ComfyUI-AnimateDiff-Evolved
   ComfyUI-fastblend
   ComfyUI-Impact-Pack
   ComfyUI-Manager
   ComfyUI-AudioScheduler
   was-node-suite-comfyui
   comfyui_controlnet_aux
   comfy_mtb
   ComfyUI_VLM_nodes
   SeargeSDXL
   ComfyUI-Crystools
   comfyui_segment_anything
   comfyui-reactor-node
   ComfyUI-DragNUWA
   Installed nodes:

BIG IFs:
If some nodes are missing from this list but there's a workflow using them in the folders, maybe those have been added natively into Comfyui or I'm no longer using them for compatibility issues between packages.
If some models can't be found, open an Issue highlighting the workflow's name and reporting the model's name so my search can be faster.

Hop into Banodoco Discord :)
