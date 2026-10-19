# Awesome AI Craft [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

> A curated list of awesome AI-powered creative craft projects, generative art engines, clones, suites, and toolkits for digital, audiovisual, and physical creation.

Inspired by [awesome-javascript](https://github.com/sorrycc/awesome-javascript).

---

## Contents

- [Awesome AI Craft](#awesome-ai-craft)
  - [Image Generation & Art](#image-generation--art)
    - [Foundation Models](#foundation-models)
    - [User Interfaces & Workflows](#user-interfaces--workflows)
    - [Image Editing & Inpainting](#image-editing--inpainting)
    - [Style Transfer](#style-transfer)
    - [Super Resolution & Upscaling](#super-resolution--upscaling)
    - [Background Removal & Matting](#background-removal--matting)
    - [Colorization & Restoration](#colorization--restoration)
    - [Face Generation & Manipulation](#face-generation--manipulation)
    - [Logo & Icon Design](#logo--icon-design)
    - [Prompt Engineering & Interrogation](#prompt-engineering--interrogation)
  - [Video & Animation](#video--animation)
    - [Video Generation](#video-generation)
    - [Video Editing & AI Agents](#video-editing--ai-agents)
    - [Motion & Animation](#motion--animation)
    - [VFX & Visual Effects](#vfx--visual-effects)
    - [Face Swap & Live Streaming](#face-swap--live-streaming)
    - [Computational Photography & Camera](#computational-photography--camera)
  - [3D & Spatial Computing](#3d--spatial-computing)
    - [3D Mesh & Asset Generation](#3d-mesh--asset-generation)
    - [NeRF & Gaussian Splatting](#nerf--gaussian-splatting)
    - [3D Textures & Material Generation](#3d-textures--material-generation)
    - [Scene Generation & Virtual Worlds](#scene-generation--virtual-worlds)
    - [Motion Capture & Pose Estimation](#motion-capture--pose-estimation)
  - [Audio & Music](#audio--music)
    - [Music Generation](#music-generation)
    - [Symbolic Music & MIDI Composition](#symbolic-music--midi-composition)
    - [Sound Effects & Foley Generation](#sound-effects--foley-generation)
    - [Voice Synthesis & TTS](#voice-synthesis--tts)
    - [Voice Cloning & Timbre Transfer](#voice-cloning--timbre-transfer)
    - [Voice Conversion](#voice-conversion)
    - [Singing Voice Synthesis](#singing-voice-synthesis)
    - [Audio Enhancement & Restoration](#audio-enhancement--restoration)
    - [Audio Source Separation](#audio-source-separation)
    - [Speech Recognition & Audio Analysis](#speech-recognition--audio-analysis)
    - [AI DJ & Smart Mixing](#ai-dj--smart-mixing)
  - [Creative Writing & Storytelling](#creative-writing--storytelling)
    - [Fiction & Story Generation](#fiction--story-generation)
    - [Screenwriting & Scriptwriting](#screenwriting--scriptwriting)
    - [Comics & Manga Creation](#comics--manga-creation)
    - [Memes & Social Content](#memes--social-content)
  - [Physical Craft, Textiles & Fashion](#physical-craft-textiles--fashion)
    - [Knitting, Crochet & Textiles](#knitting-crochet--textiles)
    - [Fashion & Virtual Try-On](#fashion--virtual-try-on)
    - [Architecture & Interior Design](#architecture--interior-design)
  - [Game Dev & Asset Generation](#game-dev--asset-generation)
    - [Sprites & 2D Game Assets](#sprites--2d-game-assets)
    - [Game Worlds & Level Generation](#game-worlds--level-generation)
  - [Design & UI Engineering](#design--ui-engineering)
    - [UI & Wireframe Generation](#ui--wireframe-generation)
    - [Typography & Font Generation](#typography--font-generation)
    - [Slide & Presentation Generation](#slide--presentation-generation)
    - [Avatars & Digital Humans](#avatars--digital-humans)
    - [Marketing & Advertising Creatives](#marketing--advertising-creatives)
  - [Multi-Modal Creative Platforms](#multi-modal-creative-platforms)
- [Community & Resources](#community--resources)
- [Other Awesome Lists](#other-awesome-lists)
- [Contributing](#contributing)

----

## Image Generation & Art

### Foundation Models
*Open-weight models, architectures, and libraries that generate images from text or sketches.*

* [FLUX](https://github.com/black-forest-labs/flux) - SOTA open-weights image generation by Black Forest Labs, excelling at prompt fidelity, photorealism, and text rendering.
* [Stable Diffusion](https://github.com/CompVis/stable-diffusion) - The pioneering open-source latent diffusion model that sparked the open AI art movement.
* [Stable Diffusion XL (SDXL)](https://github.com/Stability-AI/generative-models) - Stability AI's flagship high-resolution latent diffusion model.
* [Stable Diffusion 3 / 3.5](https://github.com/Stability-AI/sd3.5) - Multimodal Diffusion Transformer (MMDiT) architecture with refined typography and composition.
* [Diffusers](https://github.com/huggingface/diffusers) - Hugging Face's industry-standard Python library for state-of-the-art diffusion models across image and audio.
* [PixArt-Sigma](https://github.com/PixArt-alpha/PixArt-sigma) - Weak-to-strong training Diffusion Transformer (DiT) supporting 4K resolution at low computational cost.
* [Kandinsky 3](https://github.com/ai-forever/Kandinsky-3) - Open-source text-to-image diffusion architecture with strong multilingual understanding.
* [Hunyuan-DiT](https://github.com/Tencent/HunyuanDiT) - Tencent's open-source multi-resolution Diffusion Transformer with fine-grained multi-turn prompt control.
* [Würstchen](https://github.com/dome272/Wuerstchen) - Ultra-efficient text-to-image architecture using extreme latent compression (up to 42x) for fast training and inference.
* [Playground v2.5](https://huggingface.co/playgroundai/playground-v2.5-1024px-aesthetic) - Aesthetic-optimized diffusion model built on SDXL for rich color and lighting rendition.
* [Midjourney](https://www.midjourney.com/) - Commercial generative art service renowned for cinematic aesthetics and painterly styles.
* [DALL·E 3](https://openai.com/dall-e-3) - OpenAI's advanced text-to-image model integrated with ChatGPT for high prompt comprehension.
* [Adobe Firefly](https://www.adobe.com/products/firefly.html) - Commercially safe generative model family integrated into Adobe Photoshop, Illustrator, and Express.

### User Interfaces & Workflows
*Graphical interfaces, node environments, and local launchers to control diffusion pipelines.*

* [ComfyUI](https://github.com/comfyanonymous/ComfyUI) - Powerful node-based visual workflow GUI for modular multi-stage generative pipelines.
* [AUTOMATIC1111 WebUI](https://github.com/AUTOMATIC1111/stable-diffusion-webui) - The definitive browser-based interface for Stable Diffusion with hundreds of community extensions.
* [Stable Diffusion WebUI Forge](https://github.com/lllyasviel/stable-diffusion-webui-forge) - Lightweight, high-performance A1111 fork with optimized VRAM management and FLUX support.
* [InvokeAI](https://github.com/invoke-ai/InvokeAI) - Creative engine for professional visual artists with unified canvas, node editing, and board management.
* [Fooocus](https://github.com/lllyasviel/Fooocus) - Minimalist, Midjourney-like interface that optimizes prompt processing and styling automatically.
* [Stability Matrix](https://github.com/LykosAI/StabilityMatrix) - Multi-platform manager and launcher for installing and sharing models across A1111, ComfyUI, InvokeAI, and Fooocus.
* [SD.Next](https://github.com/vladmandic/automatic) - Advanced WebUI fork with broad backend support (Diffusers, ONNX, DirectML) and experimental architectures.
* [Draw Things](https://drawthings.ai/) - Native macOS and iOS app for running Stable Diffusion locally on Apple Silicon via Metal.
* [DiffusionBee](https://github.com/divamgupta/diffusionbee-stable-diffusion-ui) - One-click macOS desktop application for running Stable Diffusion completely offline.
* [EasyDiffusion](https://github.com/easydiffusion/easydiffusion) - Hassle-free one-click installer and browser interface for running SD on Windows, Linux, and Mac.

### Image Editing & Inpainting
*Techniques and tools for modifying existing images, replacing regions, and extending canvases.*

* [IOPaint](https://github.com/Sanster/IOPaint) - Open-source AI inpainting and outpainting tool powered by LaMa, PowerPaint, and SDXL.
* [ControlNet](https://github.com/lllyasviel/ControlNet) - Neural network structure to add spatial conditions (edges, poses, depth) to diffusion models.
* [IP-Adapter](https://github.com/tencent-ailab/IP-Adapter) - Image prompt adapter enabling reference-image-guided generation and style injection without finetuning.
* [PowerPaint](https://github.com/open-mmlab/PowerPaint) - High-quality task-specific inpainting model for object insertion, removal, and shape-guided filling.
* [Step1X-Edit](https://github.com/stepfun-ai/Step1X-Edit) - Open-source instruction-based image editing model rivaling proprietary editing APIs.
* [BrushEdit](https://github.com/TencentARC/BrushEdit) - Instruction-based image editing framework pairing MLLMs with dual-branch inpainting.
* [Instruct-Pix2Pix](https://github.com/timothybrooks/instruct-pix2pix) - Edits images following human-written natural language instructions without masks.
* [DragGAN](https://github.com/XingangPan/DragGAN) - Interactive point-based image editing allowing users to drag pixels to morph object structures.
* [LaMa](https://github.com/advimman/lama) - Resolution-robust large mask inpainting with Fourier convolutions for high-fidelity object removal.
* [IntraPaint](https://github.com/centuryglass/IntraPaint) - Desktop app bridging traditional digital painting canvas tools with generative AI inpainting.

### Style Transfer
*Transfer artistic styles, textures, and brushstrokes across images.*

* [AdaIN-style](https://github.com/xunhuang1995/AdaIN-style) - Real-time arbitrary style transfer via Adaptive Instance Normalization.
* [pytorch-AdaIN](https://github.com/naoto0804/pytorch-AdaIN) - Clean, modular PyTorch implementation of arbitrary artistic style transfer.
* [neural-style](https://github.com/jcjohnson/neural-style) - The classic Lua/Torch implementation of artistic neural style transfer by Justin Johnson.
* [neural-style-tf](https://github.com/cysmith/neural-style-tf) - Comprehensive TensorFlow implementation of artistic neural style transfer algorithms.
* [fast-neural-style](https://github.com/pytorch/examples/tree/main/fast_neural_style) - PyTorch's official implementation of feed-forward fast neural style transfer.
* [style2paints](https://github.com/lllyasviel/style2paints) - AI-powered sketch colorization and line art shading specifically designed for anime/illustration.
* [Awesome-Style-Transfer-with-Diffusion-Models](https://github.com/Westlake-AGI-Lab/Awesome-Style-Transfer-with-Diffusion-Models) - Research collection tracking diffusion-based artistic style transfer.

### Super Resolution & Upscaling
*Enhance detail, restore degraded textures, and enlarge images with deep learning.*

* [Real-ESRGAN](https://github.com/xinntao/Real-ESRGAN) - Practical blind super-resolution algorithm for general image and video upscaling.
* [Upscayl](https://github.com/upscayl/upscayl) - Free, open-source desktop AI image upscaler built with Vulkan and Real-ESRGAN.
* [Real-ESRGAN-ncnn-vulkan](https://github.com/xinntao/Real-ESRGAN-ncnn-vulkan) - Portable C++ Real-ESRGAN binary with no Python or CUDA requirements.
* [chaiNNer](https://github.com/chaiNNer-org/chaiNNer) - Node-based image processing GUI for chaining super-resolution, restoration, and color models.
* [SwinIR](https://github.com/JingyunLiang/SwinIR) - Image restoration using Swin Transformer for classical and real-world image super-resolution.
* [BasicSR](https://github.com/XPixelGroup/BasicSR) - Open-source deep learning image and video super-resolution and restoration toolbox.
* [waifu2x](https://github.com/nagadomi/waifu2x) - Pioneer anime-style art upscaler and noise reduction tool based on deep convolutional networks.
* [ESRGAN](https://github.com/xinntao/ESRGAN) - Enhanced Super-Resolution Generative Adversarial Networks for photorealistic perceptual quality.
* [Topaz Gigapixel AI](https://www.topazlabs.com/gigapixel) - Commercial desktop tool for upscaling images up to 600% with high sharpness.

### Background Removal & Matting
*Isolate subjects, segment cutouts, and extract transparent alpha mattes.*

* [rembg](https://github.com/danielgatis/rembg) - Ubiquitous CLI and Python library for removing image backgrounds using U2-Net, BiRefNet, and IS-Net.
* [BiRefNet](https://github.com/ZhengPeng7/BiRefNet) - State-of-the-art bilateral reference network for high-resolution edge segmentation (fine hair, glass, fur).
* [backgroundremover](https://github.com/nadermx/backgroundremover) - Command line tool to remove background from images and videos using PyTorch.
* [Segment Anything (SAM)](https://github.com/facebookresearch/segment-anything) - Meta's foundation model for promptable segmentation via point clicks, bounding boxes, or masks.
* [MODNet](https://github.com/ZHKKKe/MODNet) - Real-time trimap-free portrait matting model for portrait photos and webcam video feeds.
* [U-2-Net](https://github.com/xuebinqin/U-2-Net) - Salient object detection network powering many modern background-subtraction engines.
* [background-removal-js](https://github.com/imgly/background-removal-js) - In-browser background removal via WebAssembly and ONNX Runtime with zero server dependencies.
* [Rembg-Fuse](https://github.com/Akascape/Rembg-Fuse) - Open-source rembg plugin for DaVinci Resolve Fusion compositing workflows.
* [remove.bg](https://www.remove.bg/) - Popular commercial web service and API for automatic image background cutouts.

### Colorization & Restoration
*Colorize black-and-white archives and restore vintage photography.*

* [DeOldify](https://github.com/jantic/DeOldify) - Groundbreaking open-source project using NoGAN training to colorize and restore historical photos and video.
* [DDColor](https://github.com/piddnad/DDColor) - Dual-decoder colorization model producing vivid, contextually aware realistic colors on grayscale images.
* [InstColorization](https://github.com/ericsujw/InstColorization) - Instance-aware image colorization combining object detection with full-scene colorization networks.
* [Colorize](https://github.com/richzhang/colorization) - Seminal deep learning automatic image colorization network by Richard Zhang et al.
* [DeOldify-on-Browser](https://github.com/akbartus/DeOldify-on-Browser) - Web-based client-side DeOldify running via ONNX Runtime without Python.
* [Palette.fm](https://palette.fm/) - Commercial web-based photo colorizer with selectable artistic palettes.

### Face Generation & Manipulation
*Generate synthetic faces, perform face restorations, and swap character identities.*

* [StyleGAN3](https://github.com/NVlabs/stylegan3) - NVIDIA's alias-free generative adversarial network for photorealistic synthetic face generation.
* [FaceFusion](https://github.com/facefusion/facefusion) - Next-generation modular face-swapping and face-enhancement framework with an interactive GUI.
* [CodeFormer](https://github.com/sczhou/CodeFormer) - Robust transformer-based face restoration algorithm with adjustable fidelity parameters.
* [GFPGAN](https://github.com/TencentARC/GFPGAN) - Generative facial prior GAN for practical blind face restoration and enhancement.
* [InsightFace](https://github.com/deepinsight/insightface) - Industry-standard 2D/3D face analysis, recognition, alignment, and face-swapping library.
* [DeepFaceLab](https://github.com/iperov/DeepFaceLab) - Foundational open-source deepfake tool with full-pipeline extraction, training, and composition.
* [Arc2Face](https://github.com/foivospar/Arc2Face) - Foundation model for generating identity-consistent human faces directly from face embeddings.
* [sd-webui-reactor](https://github.com/Gourieff/sd-webui-reactor) - Fast, lightweight face swap extension for AUTOMATIC1111 Stable Diffusion WebUI.
* [ThisPersonDoesNotExist](https://thispersondoesnotexist.com/) - Web demo demonstrating continuous generation of synthetic human portraits with StyleGAN.

### Logo & Icon Design
*AI-driven generation of brand identities, logos, app icons, and vector symbols.*

* [LogoCreator](https://github.com/Nutlope/logocreator) - Open-source AI logo generator powered by FLUX and Together AI for rapid brand ideation.
* [AI Logo Studio](https://github.com/SamurAIGPT/ai-logo-studio) - Next.js SaaS template for text-to-logo and sketch-to-logo production pipelines.
* [ai-icon-generator](https://github.com/samzong/ai-icon-generator) - Open-source utility for batch generating application icons and UI badges.
* [LogoForge](https://github.com/centralpigeonnippers/ai-logo-maker) - Offline, privacy-first desktop AI logo studio using localized ONNX models.
* [Looka](https://looka.com/) - Commercial AI brand generation platform for logos, color palettes, and stationery kits.

### Prompt Engineering & Interrogation
*Extract text descriptions from imagery and optimize prompt structures.*

* [CLIP Interrogator](https://github.com/pharmapsychotic/clip-interrogator) - Analyzes images to generate optimized Stable Diffusion prompts using CLIP and BLIP.
* [MagicPrompt](https://huggingface.co/Gustavosta/MagicPrompt-Stable-Diffusion) - Fine-tuned GPT-2 model trained on creative prompts for automatic text expansion.
* [Promptist](https://github.com/microsoft/LMOps/tree/main/promptist) - Microsoft's reinforcement learning model that rewrites user inputs for diffusion models.
* [Civitai](https://civitai.com/) - Major community platform for sharing models, checkpoints, LoRAs, and prompt recipes.
* [PromptHero](https://prompthero.com/) - Curated prompt repository for Midjourney, Stable Diffusion, and DALL-E.

----

## Video & Animation

### Video Generation
*Open and closed generative models capable of synthesizing fluid video from text and images.*

* [CogVideoX](https://github.com/THUDM/CogVideo) - Tsinghua/Zhipu AI's open-weights video diffusion model family (2B & 5B) with high motion coherence.
* [HunyuanVideo](https://github.com/Tencent-Hunyuan/HunyuanVideo) - Tencent's open-weights text-to-video foundation model with cinematic visual fidelity.
* [Mochi 1](https://github.com/genmoai/mochi) - 10B-parameter open video model by Genmo utilizing Asymmetric Diffusion Transformer architecture.
* [LTX-Video](https://github.com/Lightricks/LTX-Video) - Real-time open-source video generation model optimized for consumer hardware.
* [Open-Sora](https://github.com/hpcaitech/Open-Sora) - Open-source initiative democratizing Sora-style large-scale video generation pipelines.
* [Stable Video Diffusion](https://github.com/Stability-AI/generative-models) - Foundational latent video diffusion model for image-to-video animation by Stability AI.
* [SkyReels-V2](https://github.com/SkyReels/SkyReels-V2) - Cinematic video generation utilizing AutoRegressive Diffusion-Forcing for multi-shot storytelling.
* [Sora](https://sora.com) - OpenAI's pioneering text-to-video diffusion model capable of generating complex multi-character scenes.
* [Runway Gen-3](https://runwayml.com) - Commercial video synthesis platform with camera motion controls and multi-track timelines.
* [Kling AI](https://klingai.com) - Cinematic AI video generation platform with physics simulation and built-in lip-sync.
* [Luma Dream Machine](https://lumalabs.ai/dream-machine) - High-speed commercial video generator creating realistic action and cinematic scenes.
* [Pika](https://pika.art) - Accessible AI video platform with regional canvas modification and sound effect synthesis.

### Video Editing & AI Agents
*AI-assisted timelines, intelligent editors, and programmatic video agents.*

* [OpenReel](https://github.com/openreel/openreel) - Open-source, local-first multi-track video editor enabling human-AI co-editing workflows.
* [Director](https://github.com/video-db/Director) - Agentic framework for programmatic video editing, trimming, and automated manipulations.
* [JoyAI-Video-Edit](https://github.com/JoyAI-Video-Edit/JoyAI-Video-Edit) - Real-time instruction-guided video editing using autoregressive diffusion models.
* [diffusionstudio/agent](https://github.com/diffusionstudio/agent) - MCP-enabled agent framework for programmatic video cutting, montage, and export.
* [FreeVideo](https://github.com/FlashML-org/FreeVideo) - Local runner for heavy video models with dynamic VRAM memory scaling.

### Motion & Animation
*Interpolate motion, animate stationary artwork, and model human kinematics.*

* [AnimateDiff](https://github.com/guoyww/AnimateDiff) - Motion module that animates personalized Stable Diffusion checkpoints without retraining.
* [PIA](https://github.com/open-mmlab/PIA) - Personalized Image Animator transforming static concept illustrations into animated loops.
* [FollowYourClick](https://github.com/mayuelala/FollowYourClick) - Regional image animation directed by interactive point clicks and text prompts.
* [Animato](https://github.com/otdnnc/Animato) - Automates Blender character animation from rigged 3D meshes using AI-generated scripts.
* [MDM (Motion Diffusion Model)](https://github.com/GuyTevet/motion-diffusion-model) - Classifier-free diffusion framework for text-to-human-motion generation.
* [MotionGPT](https://github.com/OpenMotionLab/MotionGPT) - Treats 3D human motion as a discrete language for unified motion generation and captioning.
* [MoMask](https://github.com/EricGuo5513/momask-codes) - Masked modeling framework for fine-grained text-driven human motion synthesis.

### VFX & Visual Effects
*Rotoscoping, depth extraction, alpha matting, and visual compositing.*

* [SAM 2 (Segment Anything 2)](https://github.com/facebookresearch/sam2) - Meta's foundation model for promptable visual segmentation across images and full video streams.
* [Depth Anything V2](https://github.com/DepthAnything/Depth-Anything-V2) - Highly robust monocular depth estimation foundation model for parallax and 3D compositing.
* [MatAnyone](https://github.com/pq-yang/MatAnyone) - Fine-grained video matting extracting hair and clothing edges for studio-grade alpha mattes.
* [Cutie-Roto](https://github.com/Zarxrax/Cutie-Roto) - Desktop rotoscoping application serving as an open-source alternative to Adobe Roto Brush.
* [RotoAI](https://github.com/sPappalard/RotoAI) - Video segmentation suite powered by SAM 2 and Grounding DINO for text-guided mask generation.
* [RotoForge-AI](https://github.com/MagnumVD/RotoForge-AI) - Blender add-on providing spline-prompted machine-learning rotoscoping.
* [Grounding DINO](https://github.com/IDEA-Research/GroundingDINO) - Open-set object detection marrying text queries with bounding box vision localization.

### Face Swap & Live Streaming
*Real-time facial replacement and interactive character puppets.*

* [DeepFaceLive](https://github.com/iperov/DeepFaceLive) - Real-time facial avatar swapping for PC streaming and live video calls.
* [FaceFusion](https://github.com/facefusion/facefusion) - Next-generation modular face-swapping and enhancement framework with real-time preview.
* [SimSwap](https://github.com/neuralchen/SimSwap) - Arbitrary face-swapping framework with identity preservation across video clips.
* [VisoMaster](https://github.com/visomaster/VisoMaster) - Streamlined video face replacement suite supporting multi-face tracking and webcam input.

### Computational Photography & Camera
*AI-driven exposure, RAW image signal processing, and computational optics.*

* [PhotonCamera](https://github.com/bjzhou/PhotonCamera) - Open-source Android camera app utilizing AI bokeh, multi-frame stacking, and HDR algorithms.
* [open-photo-ai](https://github.com/vegidio/open-photo-ai) - Desktop alternative to Topaz Photo AI for local sharpening, denoising, and deblurring.
* [AISP](https://github.com/mv-lab/AISP) - AI Image Signal Processing toolkit implementing learned ISPs, RAW restoration, and neural depth of field.
* [ImageGenCam](https://github.com/openai/imagegencam) - OpenAI's Raspberry Pi-based programmable AI camera pipeline.
* [DeepCamera](https://github.com/SharpAI/DeepCamera) - Local vision AI platform turning edge cameras into intelligent spatial sensors.

----

## 3D & Spatial Computing

### 3D Mesh & Asset Generation
*Generate 3D meshes, watertight geometry, and CAD-ready objects from prompts or single images.*

* [TripoSR](https://github.com/VAST-AI-Research/TripoSR) - Feed-forward 3D reconstruction generating detailed meshes from a single image in under 0.5 seconds.
* [InstantMesh](https://github.com/TencentARC/InstantMesh) - Sparse-view reconstruction and multi-view diffusion framework for single-image to 3D mesh.
* [TRELLIS](https://github.com/microsoft/TRELLIS) - Microsoft's structured latent 3D model decoding into radiance fields, 3D Gaussians, and meshes.
* [Hunyuan3D-2](https://github.com/Tencent-Hunyuan/Hunyuan3D-2) - Tencent's high-resolution 3D asset generation engine producing textured production meshes.
* [DreamGaussian](https://github.com/dreamgaussian/dreamgaussian) - Fast 3D content generation leveraging Gaussian Splatting with UV texture refinement.
* [LGM (Large Multi-View Gaussian Model)](https://github.com/3DTopia/LGM) - High-resolution 3D asset generation from multi-view images within seconds.
* [Shap-E](https://github.com/openai/shap-e) - OpenAI's conditional generative model for 3D textured meshes and implicit functions.
* [Point-E](https://github.com/openai/point-e) - OpenAI's system for synthesizing 3D point clouds from text prompts.
* [threestudio](https://github.com/threestudio-project/threestudio) - Unified open-source framework for text-to-3D and image-to-3D research.
* [Meshroom](https://github.com/alicevision/meshroom) - Open-source 3D reconstruction and photogrammetry pipeline based on AliceVision.

### NeRF & Gaussian Splatting
*Radiance fields, volumetric rendering, and point-based splats for real-time 3D view synthesis.*

* [Nerfstudio](https://github.com/nerfstudio-project/nerfstudio) - Modular, developer-friendly framework for creating, training, and exploring NeRF and Gaussian Splatting.
* [SuGaR](https://github.com/Anttwo/SuGaR) - Surface-Aligned Gaussian Splatting for extracting mesh geometry and textures from splats.
* [4DGaussians](https://github.com/hustvl/4DGaussians) - Real-time dynamic scene rendering using 4D Gaussian Splatting across animated timelines.
* [MiDaS](https://github.com/isl-org/MiDaS) - Intel's foundational monocular depth estimation network for 3D spatial reconstruction.

### 3D Textures & Material Generation
*Synthesize physically based rendering (PBR) maps, diffuse textures, and materials.*

* [Material Anything](https://github.com/3DTopia/MaterialAnything) - Generates full PBR material maps (albedo, roughness, metallic, normal) for arbitrary 3D meshes.
* [Paint3D](https://github.com/OpenTexture/Paint3D) - Generates lighting-free, high-resolution textures for untextured 3D meshes using diffusion.
* [Material Palette](https://github.com/astra-vision/MaterialPalette) - Decomposes single reference photographs into editable SVBRDF material maps.
* [StableGen](https://github.com/sakalond/StableGen) - Blender add-on connecting generative diffusion models to 3D texture mapping workflows.
* [texture-synthesis](https://github.com/EmbarkStudios/texture-synthesis) - Rust library for example-based multiresolution texture synthesis by Embark Studios.
* [TEXTure](https://github.com/TEXTurePaper/TEXTurePaper) - Text-guided 3D mesh texturing using iterative multi-angle diffusion painting.

### Scene Generation & Virtual Worlds
*Synthesize complete navigable 3D environments, skyboxes, and procedural worlds.*

* [WorldGen](https://github.com/ZiYang-xie/WorldGen) - Generates complete indoor and outdoor 3D scenes from text or photos into meshes and splats.
* [Infinigen](https://github.com/princeton-vpa/infinigen) - Princeton's procedural generator creating photorealistic 3D natural worlds inside Blender.
* [Holodeck](https://github.com/allenai/Holodeck) - Generates interactive 3D embodied simulation environments from language prompts.
* [EdenLive](https://github.com/VAST-AI-Research/EdenLive) - Real-time neural renderer bridging game engine loops and generative visual synthesis.
* [Blockade Labs Skybox](https://skybox.blockadelabs.com) - Commercial tool generating seamless 360° panoramic skybox environments from text.

### Motion Capture & Pose Estimation
*Extract 3D skeleton keypoints, hand gestures, and body poses from monocular video.*

* [MediaPipe](https://github.com/google-ai-edge/mediapipe) - Google's real-time cross-platform framework for tracking 33 body landmarks, hands, and facial geometry.
* [OpenPose](https://github.com/CMU-Perceptual-Computing-Lab/openpose) - Landmark multi-person real-time 2D/3D pose detection system developed at CMU.
* [MMPose](https://github.com/open-mmlab/mmpose) - PyTorch-based pose estimation toolbox featuring RTMPose and ViTPose models.
* [Sapiens](https://github.com/facebookresearch/sapiens) - Meta's foundation models for human-centric vision tasks (pose, depth, surface normals, segmentation).
* [HaMeR](https://github.com/geopavlakos/hamer) - High-fidelity 3D hand mesh recovery and reconstruction from monocular 2D images.
* [4D-Humans (HMR 2.0)](https://github.com/shubham-goel/4D-Humans) - SOTA 3D human mesh recovery and motion tracking from arbitrary in-the-wild video.

----

## Audio & Music

### Music Generation
*Generative audio models and foundation frameworks synthesizing complete music tracks.*

* [AudioCraft (MusicGen)](https://github.com/facebookresearch/audiocraft) - Meta's open-source library for deep learning audio generation, featuring MusicGen and AudioGen.
* [ACE-Step](https://github.com/ace-step/ACE-Step) - Open-source foundation model generating complete songs with vocals in 50+ languages on <4GB VRAM.
* [YuE](https://github.com/multimodal-art-projection/YuE) - Open-source full-length song generation model producing coherent lyrics, singing, and arrangements.
* [DiffRhythm](https://github.com/ASLP-lab/DiffRhythm) - Fast latent diffusion model synthesizing structured full-length tracks from lyric sheets.
* [Stable Audio Open](https://github.com/Stability-AI/stable-audio-tools) - Stability AI's open-weight latent diffusion model for audio synthesis and sound design.
* [Jukebox](https://github.com/openai/jukebox) - OpenAI's pioneering neural net for singing and instrumental music generation in raw audio.
* [Suno](https://suno.com) - Leading commercial platform synthesizing broadcast-ready songs with vocals across musical genres.
* [Udio](https://udio.com) - Commercial AI music platform celebrated for vocal realism and complex musical styles.

### Symbolic Music & MIDI Composition
*Algorithmic composition, MIDI sequencing, and musical score creation.*

* [Magenta](https://github.com/magenta/magenta) - Google's research project exploring machine learning for music composition, MIDI generation, and creative tools.
* [basic-pitch](https://github.com/spotify/basic-pitch) - Spotify's lightweight neural polyphonic audio-to-MIDI converter with pitch bend tracking.
* [Text2midi](https://github.com/AMAAI-Lab/Text2midi) - Generates multi-track structured MIDI files from natural language descriptions.
* [midi-model](https://github.com/SkyTNT/midi-model) - Transformer model for symbolic music composition and expressive piano sequencing.
* [MidiEditor_AI](https://github.com/happytunesai/MidiEditor_AI) - AI-assisted MIDI sequencer with natural language copilot editing.
* [Amphion](https://github.com/open-mmlab/Amphion) - Toolkit for audio, music, and speech generation with symbolic composition modules.

### Sound Effects & Foley Generation
*Synthesize ambient soundscapes, movie Foley, and synchronized video audio.*

* [AudioLDM 2](https://github.com/haoheliu/AudioLDM2) - Versatile latent diffusion architecture for text-to-audio, SFX, and ambient generation.
* [AudioGen](https://github.com/facebookresearch/audiocraft) - Meta's autoregressive model for generating realistic environmental sound effects from text.
* [FoleyCrafter](https://github.com/ymzhang319/FoleyCrafter) - Framework synthesizing video-synchronized Foley sound effects using semantic and temporal adapters.
* [Foley-Omni](https://github.com/NJU-Speech/Foley-Omni) - Multimodal model generating synchronized speech, SFX, and ambient background scores for video.
* [Stable Audio Tools](https://github.com/Stability-AI/stable-audio-tools) - Training and inference suite for audio latent diffusion models.
* [ElevenLabs Sound Effects](https://elevenlabs.io/sound-effects) - Commercial AI sound effects generator from natural language prompts.

### Voice Synthesis & TTS
*Neural text-to-speech models producing expressive, conversational, and multilingual voice.*

* [F5-TTS](https://github.com/SWivid/F5-TTS) - Non-autoregressive speech synthesis using flow matching with DiT; zero-shot cloning with zero alignment.
* [Bark](https://github.com/suno-ai/bark) - Transformer-based generative audio model producing speech, whispers, laughter, and sighs.
* [Coqui TTS](https://github.com/coqui-ai/TTS) - Comprehensive deep learning toolkit for text-to-speech with XTTS multi-lingual zero-shot cloning.
* [Piper](https://github.com/rhasspy/piper) - Ultra-fast local neural TTS engine optimized for edge devices like Raspberry Pi.
* [StyleTTS 2](https://github.com/yl4579/StyleTTS2) - Style diffusion text-to-speech system with human-level prosody and natural rhythm.
* [ChatTTS](https://github.com/2noise/ChatTTS) - Conversational speech model generating natural conversational pauses, laughter, and filler words.
* [MeloTTS](https://github.com/myshell-ai/MeloTTS) - Lightweight real-time multilingual TTS running on standard consumer CPUs.
* [Parler-TTS](https://github.com/huggingface/parler-tts) - Controllable TTS model where voice timbre and recording acoustics are described via text.
* [CosyVoice](https://github.com/FunAudioLLM/CosyVoice) - Alibaba's multilingual speech synthesizer with zero-shot cloning and streaming output.

### Voice Cloning & Timbre Transfer
*Clone vocal characteristics from short reference recordings.*

* [OpenVoice](https://github.com/myshell-ai/OpenVoice) - Instant tone-color cloning framework with granular control over emotion, accent, and pitch.
* [GPT-SoVITS](https://github.com/RVC-Boss/GPT-SoVITS) - Few-shot voice cloning and cross-lingual TTS requiring just 1 minute of sample audio.
* [XTTS-v2](https://huggingface.co/coqui/XTTS-v2) - Cross-lingual zero-shot voice cloning engine operating from a 3-second audio snippet.
* [TortoiseTTS](https://github.com/neonbjb/tortoise-tts) - High-fidelity multi-voice synthesizer using autoregressive decoders and diffusion.

### Voice Conversion
*Transform spoken timbre or singing voice from one person to another in real-time.*

* [RVC (Retrieval-based Voice Conversion)](https://github.com/RVC-Project/Retrieval-based-Voice-Conversion-WebUI) - Dominant voice conversion framework using VITS and HuBERT features with fast training.
* [so-vits-svc-fork](https://github.com/34j/so-vits-svc-fork) - Actively maintained fork of SoftVC VITS for expressive singing voice conversion.
* [Seed-VC](https://github.com/Plachtaa/seed-vc) - Zero-shot real-time voice and singing conversion without training individual target models.
* [w-okada Voice Changer](https://github.com/w-okada/voice-changer) - Cross-platform real-time voice changer client for live streaming and gaming.
* [Applio](https://github.com/IAHispano/Applio) - Modernized, extensible RVC-based voice conversion tool with an intuitive web GUI.

### Singing Voice Synthesis
*Synthesize melodic singing voices from musical scores and phonetic lyrics.*

* [DiffSinger](https://github.com/MoonInTheRiver/DiffSinger) - Diffusion-based singing voice synthesis system producing expressive, realistic vocal tracks.
* [OpenUtau](https://github.com/stakira/OpenUtau) - Open-source singing synthesizer and DAW supporting DiffSinger, NNSVS, and traditional voicebanks.
* [NNSVS](https://github.com/nnsvs/nnsvs) - Neural network-based singing voice synthesis toolkit for creating and training custom vocalists.
* [VISinger 2](https://github.com/zhangyongmao/VISinger2) - End-to-end singing voice synthesizer with conditional VAE and adversarial training.

### Audio Enhancement & Restoration
*Eliminate noise, repair clipping, restore bandwidth, and recover vintage recordings.*

* [DeepFilterNet](https://github.com/Rikorose/DeepFilterNet) - Real-time deep learning audio noise suppression with low computational latency.
* [Resemble Enhance](https://github.com/resemble-ai/resemble-enhance) - Dual-stage neural framework for speech denoising and synthetic bandwidth extension.
* [AudioSR](https://github.com/haoheliu/AudioSR) - Universal diffusion-based audio super-resolution upscaling any audio sample to 48kHz.
* [Apollo](https://github.com/JusperLee/Apollo) - Restores compressed MP3 audio files back into studio-quality high-resolution sound.
* [Matchering](https://github.com/sergree/matchering) - Automated audio mastering tool matching your mix to a reference track's tonal profile.

### Audio Source Separation
*Isolate vocal stems, drums, bass, and individual instruments from finished mixes.*

* [Demucs](https://github.com/facebookresearch/demucs) - Meta's state-of-the-art music source separation model using Hybrid Transformer U-Net architecture.
* [Ultimate Vocal Remover (UVR5)](https://github.com/Anjok07/ultimatevocalremovergui) - Desktop application packing Demucs, MDX-Net, and VR models for stem extraction and de-reverberation.
* [Spleeter](https://github.com/deezer/spleeter) - Deezer's fast, widely deployed source separation library with pre-trained 2, 4, and 5-stem models.
* [BandIt Plus](https://github.com/kwatcharasupat/bandit) - Neural network separating cinema audio into distinct dialogue, music, and SFX stems.
* [Music-Source-Separation-Training](https://github.com/ZFTurbo/Music-Source-Separation-Training) - Benchmark training suite for BS-RoFormer, Mel-Band RoFormer, and HTDemucs.

### Speech Recognition & Audio Analysis
*Transcribe speech, detect musical structures, and analyze audio features.*

* [Whisper](https://github.com/openai/whisper) - OpenAI's robust general-purpose speech recognition model across 90+ languages.
* [faster-whisper](https://github.com/SYSTRAN/faster-whisper) - CTranslate2-accelerated Whisper reimplementation delivering up to 4x faster transcription.
* [WhisperX](https://github.com/m-bain/whisperX) - Whisper transcription enhanced with forced alignment timestamps and speaker diarization.
* [whisper.cpp](https://github.com/ggerganov/whisper.cpp) - Pure C/C++ port of Whisper for high-efficiency CPU inference on Mac, Linux, and mobile.
* [Essentia](https://github.com/MTG/essentia) - C++ and Python library for music information retrieval, key detection, and beat tracking.
* [Librosa](https://github.com/librosa/librosa) - Python audio and music analysis package providing building blocks for audio applications.

### AI DJ & Smart Mixing
*Automated track beatmatching, harmonic mixing, and intelligent DJ sets.*

* [auto-dj-ai](https://github.com/caffettino87/auto-dj-ai) - Browser-based auto DJ with BPM/key analysis, harmonic mixing, and Demucs stem-aware crossfading.
* [AutoDJ](https://github.com/blindndangerous/AutoDJ) - AI music continuity player utilizing MuQ embeddings and FAISS similarity for track sequencing.
* [Spotify DJ](https://newsroom.spotify.com/2023-02-22/spotify-debuts-a-new-ai-dj-right-in-your-pocket/) - Commercial personalized AI DJ combining curation algorithms with dynamic voice commentary.

----

## Creative Writing & Storytelling

### Fiction & Story Generation
*Assistants, engines, and workspaces tailored for long-form narrative fiction.*

* [OpenWrite](https://github.com/ilrein/openwrite) - Open-source writing platform for novelists and screenwriters with node-based visual story maps.
* [Novel-Studio](https://github.com/Xiaoyangy/novel-studio) - Local-first engine for long-form fiction featuring multi-agent world simulation and RAG memory.
* [StoryWriter](https://github.com/THU-KEG/StoryWriter) - Multi-agent research framework for long-form narrative with outline, planning, and prose agents.
* [NovelCrafter](https://novelcrafter.com) - Comprehensive novel planning and writing environment with integrated world-building Codex.
* [Sudowrite](https://sudowrite.com) - Commercial AI fiction co-writer equipped with Story Engine, sensory expansions, and pacing tools.
* [AI Dungeon](https://aidungeon.com) - Interactive narrative fiction game engine with dynamically unfolding adventures.

### Screenwriting & Scriptwriting
*Translate ideas, books, and outlines into formatted industry screenplays.*

* [Fountain-Screenwriter](https://github.com/tlorien/fountain-screenwriter) - Multi-agent pipeline turning loglines into short drama scripts with storyboard layouts.
* [Novel2Script_AI](https://github.com/LYGSYJ/Novel2Script_AI) - Adapts novels into screenplay scripts using dual-route RAG and LangGraph orchestration.
* [Story Architect (starc)](https://github.com/story-apps/starc) - Desktop narrative studio for managing story concepts, character bibles, and screenplays.
* [ActOne-Screenplay](https://github.com/BeetleBot/ActOne-Screenplay) - Screenplay writing software for desktop built around standard Fountain markup.

### Comics & Manga Creation
*Compose multi-panel visual storytelling, webtoons, and graphic novels.*

* [AIComicBuilder](https://github.com/LingyiChen-AI/AIComicBuilder) - End-to-end system turning text scripts into structured comic layouts with character consistency.
* [Comic Generator](https://github.com/Yutarop/comic-generator) - Streamlit tool generating multi-page manga panels from concise narrative prompts.
* [AI Comic Factory](https://github.com/llamagen) - Open-source ecosystem for comic strip, anime page, and webtoon generation.
* [Agent Comic Kit](https://github.com/Saeyeon-developer/agent-comic-kit) - Developer toolkit for programmatic panel layout generation and speech bubble lettering.

### Memes & Social Content
*Automated humor generation, meme layout engines, and captioning.*

* [Full-Stack-AI-Meme-Generator](https://github.com/ThioJoe/Full-Stack-AI-Meme-Generator) - End-to-end system synthesizing humorous meme captions and compositing onto image templates.
* [memegen](https://github.com/jacebrowning/memegen) - Open-source programmatic API and engine for generating captioned image memes.

----

## Physical Craft, Textiles & Fashion

### Knitting, Crochet & Textiles
*Generate stitch patterns, translate photos into needlework charts, and drive knitting machines.*

* [CrochetPARADE](https://github.com/crochetparade/crochetparade) - Domain-specific language grammar and visualizer for defining and checking 2D/3D crochet patterns.
* [YarnMaster](https://github.com/kathywu1201/AC215_YarnMaster) - Multimodal pipeline converting garment photos into step-by-step crochet instructions.
* [knittingpattern](https://github.com/fossasia/knittingpattern) - Python library providing open data specifications connecting digital patterns to knitting machines.
* [Knitwit](https://github.com/arnfred/Knitwit) - Converts digital photos into color-mapped grid patterns for hand-knitting.
* [quiltR](https://github.com/awalsh17/quiltR) - Programmatically designs geometric quilting patterns and calculates fabric cuts using R.
* [Textiles Lab](https://github.com/textiles-lab) - CMU research lab toolchains (autoknit, knitout) for computational textiles and CNC knitting machines.

### Fashion & Virtual Try-On
*Generate clothing, simulate apparel on realistic avatars, and draft production tech packs.*

* [IMAGDressing](https://github.com/muzishen/IMAGDressing) - Interactive modular apparel generation for virtual try-on with fine-grained pose and garment control.
* [OpenTryOn](https://github.com/tryonlabs/opentryon) - Open-source APIs and models for virtual garment try-on, lookbooks, and fashion editing.
* [Techpack AI Builder](https://github.com/morfemartin/techpack-ai-builder) - Translates clothing sketches into production-ready SVG tech packs with embroidery specs.
* [Fashion AI Studio](https://github.com/onwp/fashion-ai-studio) - Renders apparel items onto diverse synthetic human models across customized backdrops.

### Architecture & Interior Design
*Floor plan generation, virtual home staging, and architectural concept renders.*

* [ZyoraAI](https://github.com/iamsandeepmaddheshiya/ZyoraAI-AI-home-interior-design) - Open-source room redesign and virtual staging engine using architectural diffusion inpainting.
* [Roomsmith](https://github.com/Rumeasiyan/roomsmith) - Multi-agent interior design assistant generating floor plans, elevations, and photorealistic renders.
* [OpenHouse-3D](https://github.com/yunfanye/openhouse-3d) - Converts real estate photographs into full 3D interactive home walkthroughs.
* [Roomify](https://github.com/adrianhajdin/roomify) - Visualizer converting 2D blueprints and floor plans into photorealistic 3D interior renders.

----

## Game Dev & Asset Generation

### Sprites & 2D Game Assets
*Synthesize sprite sheets, character animations, tilesets, and pixel art.*

* [Sprite Sage](https://github.com/keystoneintelligence/spritesage) - Desktop workspace for designing, generating, and animating 2D game sprites with Godot 4 export.
* [ai-game-spritesheets](https://github.com/chongdashu/ai-game-spritesheets) - Workflow template for generating character directional walk/run/attack cycles with consistent style.
* [OhMyGame](https://github.com/WhiteTowerAI/ohmygame) - Solo game studio desktop app coordinating LLMs, image, video, and 3D generators.
* [Awesome AI Game Dev Tools](https://github.com/SubmitGame/awesome-ai-game-dev-tools) - Curated database tracking open-source AI game development utilities.

### Game Worlds & Level Generation
*Synthesize terrain maps, tile arrangements, and responsive game environments.*

* [WorldX](https://github.com/YGYOOO/WorldX) - Generates complete tile-based worlds, map hierarchies, and character behaviors from single prompts.
* [AI Game DevTools Hub](https://github.com/Yuan-ManX/ai-game-devtools) - Collection of texture generators, audio synthesizers, and pixel-art quantizers.

----

## Design & UI Engineering

### UI & Wireframe Generation
*Synthesize frontend components, design systems, and responsive web templates.*

* [screenshot-to-code](https://github.com/abi/screenshot-to-code) - Converts design screenshots and Figma files into clean React, Vue, and Tailwind code.
* [OpenPencil](https://github.com/open-pencil/open-pencil) - AI-native open-source design tool (Figma alternative) with real-time vector editing and P2P sync.
* [Penpot](https://github.com/penpot/penpot) - Leading open-source, web-based collaborative design tool based on open web standards.
* [quickmock](https://github.com/Lemoncode/quickmock) - Rapid open-source wireframing tool for designing low-fidelity UI mockups.
* [v0 by Vercel](https://v0.dev) - Commercial generative UI platform compiling natural language prompts into React/Tailwind components.

### Typography & Font Generation
*Generate typography glyphs, vector outlines, and complete font families.*

* [fewshot-font-generation](https://github.com/clovaai/fewshot-font-generation) - Collection of few-shot font generation methods including FUNIT, DM-Font, and LF-Font.
* [MX-Font](https://github.com/clovaai/mxfont) - Few-shot font generation utilizing localized character expert modules.
* [AI_Font_Generator](https://github.com/Johannes-Schall/AI_Font_Generator) - Fills missing characters in font glyph tables and designs new type styles from prompts.
* [TypographyResearchCollection](https://github.com/IShengFang/TypographyResearchCollection) - Comprehensive index tracking neural font generation and glyph style transfer papers.

### Slide & Presentation Generation
*Generate structured presentation decks, pitch decks, and visual slides.*

* [Presenton](https://github.com/presenton/presenton) - Open-source AI presentation generator supporting local Ollama and major cloud models with PPTX export.
* [Presentation-AI](https://github.com/allweonedev/presentation-ai) - Open-source Gamma alternative featuring outline-driven generation and slide templates.
* [Codex Slides](https://github.com/nexu-io/codex-slides) - Agentic presentation builder chaining research, outlining, styling, and rendering steps.
* [PPTAgent](https://github.com/icip-cas/PPTAgent) - Agentic framework providing reflective PowerPoint deck synthesis with automated layout correction.

### Avatars & Digital Humans
*Lip-synced video avatars, synthetic presenters, and customizable 2D/3D characters.*

* [Duix-Avatar](https://github.com/duixcom/Duix-Avatar) - Offline video synthesis engine for cloning digital human presenters on Windows.
* [LiveTalking](https://github.com/lipku/LiveTalking) - Real-time conversational digital human streamer with low-latency lip synchronization.
* [302.AI Avatar Generator](https://github.com/302ai/302_ai_avatar_generator) - Multi-model avatar tool supporting Hedra, OmniHuman, and LatentSync for audio-driven speech.
* [Avataaars Generator](https://github.com/fangpenlin/avataaars-generator) - React library for generating customizable vector cartoon avatar illustrations.

### Marketing & Advertising Creatives
*Produce social ad creatives, marketing collateral, and ad copy variants.*

* [OpenAdKit](https://github.com/IamRamgarhia/OpenAdKit-Open-Source-AI-Marketing-Tool) - In-browser marketing suite with AI generators for Meta, TikTok, and Google ad creatives.
* [AgenticAds](https://github.com/Shree2604/Agentic-Ads) - LangGraph-based marketing engine generating coordinated ad copy, posters, and campaign videos.
* [Ai_adcopy](https://github.com/liferacer333/Ai_adcopy) - Converts product specifications into high-converting promotional ad copy.

----

## Multi-Modal Creative Platforms
*Unified suites and orchestrators uniting image, video, audio, and language generation.*

* [ComfyUI](https://github.com/comfyanonymous/ComfyUI) - The premier node-based visual canvas uniting diffusion models, video transformers, audio generators, and LLM nodes.
* [Google Cloud Creative Studio](https://github.com/GoogleCloudPlatform/gcc-creative-studio) - Reference implementation for multi-modal text, image, video, and audio production.
* [Open-Generative-AI](https://github.com/Anil-matcha/Open-Generative-AI) - Self-hosted creative studio supporting hundreds of models across media formats.
* [n8n](https://github.com/n8n-io/n8n) - Visual workflow automation platform with deep LangChain and generative media integrations.
* [Pipecat](https://github.com/pipecat-ai/pipecat) - Open-source framework for building real-time multi-modal voice and creative AI agents.

----

## Community & Resources

* [Civitai](https://civitai.com/) - The largest hub for sharing open-weights models, LoRAs, aesthetic embeddings, and generation metadata.
* [Hugging Face](https://huggingface.co/) - The home of open machine learning models, datasets, spaces, and community papers.
* [Reddit r/StableDiffusion](https://www.reddit.com/r/StableDiffusion/) - Primary forum for discoveries, workflows, and tools across open generative media.
* [Reddit r/LocalLLaMA](https://www.reddit.com/r/LocalLLaMA/) - Community focused on running open-weights language and multimodal models on consumer hardware.

----

## Other Awesome Lists

* [awesome-generative-ai](https://github.com/steven2358/awesome-generative-ai) - Curated list of Generative AI applications and foundational models.
* [awesome-diffusion-models](https://github.com/heejkoo/Awesome-Diffusion-Models) - Collection of research papers and implementations regarding diffusion algorithms.
* [awesome-ai-art-tools](https://github.com/winter-digital/awesome-ai-art-tools) - Curated collection of creative tools for AI artists and designers.
* [awesome-deep-learning-music](https://github.com/ybayle/awesome-deep-learning-music) - Comprehensive bibliography and repository of deep learning for music.

----

## Contributing

Contributions welcome! Read the [contribution guidelines](CONTRIBUTING.md) first.

If you know of an awesome AI craft tool, library, or engine:

1. Fork this repository.
2. Create a new branch: `git checkout -b add-my-project`.
3. Add your entry in alphabetical order under the appropriate section using the standard format:
   `* [ProjectName](https://url) - Brief, objective description.`
4. Commit your changes: `git commit -m "Add ProjectName"`.
5. Push to the branch: `git push origin add-my-project`.
6. Submit a pull request.
