# Awesome-Embodied-AI
## Scene Understanding

### Image

| | Description | Paper | Code |
|------|-------|------|------|
|SAM  | Segmentation | <https://arxiv.org/abs/2304.02643> | <https://github.com/facebookresearch/segment-anything>|
|YOLO-World | Open-Vocabulary Detection | <https://arxiv.org/abs/2401.17270> |<https://github.com/AILab-CVC/YOLO-World>|

### Point Cloud

| | Description | Paper | Code |
|------|-------|------|------|
|SAM3D  | Segmentation | <https://arxiv.org/abs/2306.03908> | <https://github.com/Pointcept/SegmentAnything3D>|
|PointMixer | Understanding | <https://arxiv.org/abs/2401.17270> |<https://github.com/LifeBeyondExpectations/PointMixer>|

### Multi-Modal Grounding

| | Description | Paper | Code |
|------|-------|------|------|
|GPT4V  | MLM(Image+Language->Language) | https://arxiv.org/abs/2303.08774 | |
|Claude3-Opus  | MLM(Image+Language->Language) | https://www.anthropic.com/news/claude-3-family | |
|GLaMM | Pixel Grounding | <https://arxiv.org/abs/2311.03356> |<https://github.com/mbzuai-oryx/groundingLMM> |
|All-Seeing |Pixel Grounding | <https://arxiv.org/abs/2402.19474>| <https://github.com/OpenGVLab/all-seeing>|
|LEO | 3D | <https://arxiv.org/abs/2311.12871> |<https://github.com/embodied-generalist/embodied-generalist> |

## Data Collection

### From Video

| | Description | Paper | Code |
|------|-------|------|------|
|Vid2Robot  |  | <https://vid2robot.github.io/vid2robot.pdf> | |
|RT-Trajectory | | <https://arxiv.org/abs/2311.01977>| |
|MimicPlay||<https://mimic-play.github.io/assets/MimicPlay.pdf>| <https://github.com/j96w/MimicPlay> |

### Hardware

| | Description | Paper | Code |
|------|-------|------|------|
|UMI  | Two-Fingers | <https://arxiv.org/abs/2402.10329> |<https://github.com/real-stanford/universal_manipulation_interface> |
|DexCap | Five-Fingers| <https://dex-cap.github.io/assets/DexCap_paper.pdf>|<https://github.com/j96w/DexCap> |
|HIRO Hand|Hand-over-hand|<https://sites.google.com/view/hiro-hand>||

### Generative Simulation

| | Description | Paper | Code |
|------|-------|------|------|
|MimicGen  |  | <https://arxiv.org/abs/2310.17596> |<https://github.com/NVlabs/mimicgen_environments>|
|RoboGen || <https://arxiv.org/abs/2311.01455> |<https://github.com/Genesis-Embodied-AI/RoboGen> |

## Action Output

### Generative Imitation Learning

| | Description | Paper | Code |
|------|-------|------|------|
|Diffusion Policy||<https://arxiv.org/abs/2303.04137>| <https://github.com/real-stanford/diffusion_policy>|
|ACT||<https://arxiv.org/abs/2304.13705> | <https://github.com/tonyzhaozh/act> |

### Affordance Map

| | Description | Paper | Code |
|------|-------|------|------|
|CLIPort|Pick&Place|<https://arxiv.org/pdf/2109.12098.pdf>|<https://github.com/cliport/cliport>|
|Robo-Affordances|Contact&Post-contact trajectories|<https://arxiv.org/abs/2304.08488>|<https://github.com/shikharbahl/vrb>|
|Robo-ABC||<https://arxiv.org/abs/2401.07487>|https://github.com/TEA-Lab/Robo-ABC|
|Where2Explore|Few shot learning from semantic similarity|<https://proceedings.neurips.cc/paper_files/paper/2023/file/0e7e2af2e5ba822c9ad35a37b31b5dd4-Paper-Conference.pdf>||
|Move as You Say, Interact as You Can|Affordance to motion from diffusion model|<https://arxiv.org/pdf/2403.18036.pdf>||
|AffordanceLLM|Grounding affordance with LLM|<https://arxiv.org/pdf/2401.06341.pdf>||
|Environment-aware Affordance||<https://proceedings.neurips.cc/paper_files/paper/2023/file/bf78fc727cf882df66e6dbc826161e86-Paper-Conference.pdf>||
|OpenAD|Open-Voc Affordance Detection from point cloud|<https://www.csc.liv.ac.uk/~anguyen/assets/pdfs/2023_OpenAD.pdf>|<https://github.com/Fsoft-AIC/Open-Vocabulary-Affordance-Detection-in-3D-Point-Clouds>|
|RLAfford|End-to-End affordance learning with RL|<https://gengyiran.github.io/pdf/RLAfford.pdf>||
|General Flow|Collect affordance from video|<https://general-flow.github.io/general_flow.pdf>|<https://github.com/michaelyuancb/general_flow>|
|PreAffordance|Pre-grasping planning|<https://arxiv.org/pdf/2404.03634.pdf>||
|ScenFun3d|Fine-grained functionality&affordance in 3D scene|<https://aycatakmaz.github.io/data/SceneFun3D-preprint.pdf>|<https://github.com/SceneFun3D/scenefun3d>|

### Question&Answer from LLM

| | Description | Paper | Code |
|------|-------|------|------|
|COPA| |<https://arxiv.org/abs/2403.08248>||
|ManipLLM| |<https://arxiv.org/abs/2312.16217>||
|ManipVQA| |<https://arxiv.org/pdf/2403.11289.pdf>|https://github.com/SiyuanHuang95/ManipVQA|

### Language Corrections
| | Description | Paper | Code |
|------|-------|------|------|
|OLAF| |<https://arxiv.org/pdf/2310.17555>||
|YAYRobot| |<https://arxiv.org/abs/2403.12910>|https://github.com/yay-robot/yay_robot|

### Planning from LLM

| | Description | Paper | Code |
|------|-------|------|------|
|SayCan| API Level|<https://arxiv.org/abs/2204.01691>|<https://github.com/google-research/google-research/tree/master/saycan> |
|VILA| Prompt Level|<https://arxiv.org/abs/2311.17842>| |
| Code-as-Monitor | CVPR 2025 | <https://arxiv.org/abs/2412.04455> | <https://zhoues.github.io/Code-as-Monitor/> |
