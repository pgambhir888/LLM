# Omost

Omost is a project to convert LLM's coding capability to image generation (or more accurately, image composing) capability. 

The name `Omost` (pronunciation: almost) has two meanings: 1) everytime after you use Omost, your image is almost there; 2) the `O` mean "omni" (multi-model) and `most` means we want to get most of it.

Omost provides LLMs models that will write codes to compose image visual contents with Omost's virtual `Canvas` agent. This `Canvas` can be rendered by specific implementations of image generators to actually generate images.

Currently, we provide 3 pretrained LLM models based on Llama3 and Phi3 (see also the model notes at the end of this page).

# Get Started

Below script will run the text-conditioned relighting model:

    git clone https://github.com/lllyasviel/Omost.git
    cd Omost
    conda create -n omost python=3.10
    conda activate omost
    pip install torch torchvision --index-url https://download.pytorch.org/whl/cu121
    pip install -r requirements.txt
    python gradio_app.py

# Screenshots

# Symbols

# Baseline Implementation

# Examples

# Model Notes
