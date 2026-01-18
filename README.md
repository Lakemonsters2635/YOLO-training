# Custom Data Generation for YOLOv11 with VOCDataset and Training
## works on linux, mac, (almost on windows), and gpu machines

- there are sample images of game elements in the `sample-images` folder
- when you finish running the notebook, a new directory titled `finalProduct` will have your `.blob` file

1. Take pictures
1. Prepare environment
1. Prepare/Organize object images
3. Download VOCDataset for backing of object images
1. Overlay objects on backing images and generate YOLO labels
9000. Train model
1. Upload to Luxonis to convert to OpenVINO format
