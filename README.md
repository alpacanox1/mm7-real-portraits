# mm7-portraits
Might &amp; Magic VII portraits repainted.

![example](example.png)

Status:

NPC: 133/584

Goal:

During development of Might and Magic VII the team switched to rendering portraits instead of using stock images, unlike in the previous installment.
That change is viewed negatively by some. The project aims at repainting the portraits to make them look more like real-life photos.

How is it done:

1. The original portrait is upscaled up to 512px.
2. Face restoration algorithm (GFPGAN) is used to recover facial features.
3. Stable diffusion model in img2img mode is used to repaint the image.

Overview:

![overview](overview.png)
