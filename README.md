# Diffusion Policy

LeRobot diffusion policy implementation.

## Files

- **configuration_diffusion.py** — Policy config (hyperparameters, observation/action features, vision backbone, noise scheduler)
- **modeling_diffusion.py** — Core model (UNet, forward pass, training, action sampling)
- **processor_diffusion.py** — Preprocessing (image encoding, state processing) and postprocessing
