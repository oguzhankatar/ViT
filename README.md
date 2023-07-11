# ViT

!pip install torchinfo
from torchinfo import summary

summary(model=model, input_size=(1,3,224,224), col_names=["input_size", "output_size", "num_params", "trainable"],
        col_width=20,
        row_settings=["var_names"])
