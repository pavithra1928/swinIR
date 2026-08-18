# swinIR
SwinIR image-restoration training in Google Colab needs reliable checkpoint-based resumption after runtime interruptions. The main challenge is restoring the saved model/training state and continuing from the latest epoch when Colab GPU availability is limited.
