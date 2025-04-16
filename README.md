# Object_Detection
Object_Description using google collab
1.command:

Uses the small pre-trained YOLOv5s model,

Detects objects in the sample bus.jpg image,

Saves the result in runs/detect/exp.

✅ 2. Upload Custom Data
If you're planning to train or test on custom data:

Organize your dataset into the YOLO format (images and labels).

Upload it to Colab or mount Google Drive.

Update the dataset YAML file accordingly.

✅ 3. Train on Custom Dataset (Optional)
If you’re training a model:

python
Copy
Edit
!python train.py --img 640 --batch 16 --epochs 50 --data custom.yaml --weights yolov5s.pt
✅ 4. Evaluate or Test a Model
