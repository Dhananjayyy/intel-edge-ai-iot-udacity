To access the Model Downloader, GO to: `cd /opt/intel/openvino/deployment_tools/tools/model_downloader`

Tasks - Find and Download the Right Models
Using the [Pre-Trained Model list](https://software.intel.com/en-us/openvino-toolkit/documentation/pretrained-models):

    Human Pose Estimation  (all precision levels)
      sudo ./downloader.py --name human-pose-estimation-0001 -o /home/workspace
    Text Detection (FP16)
      sudo ./downloader.py --name text-detection-0004 --precisions FP16 -o /home/workspace
    Determining Car Type & Color (INT8)
      sudo ./downloader.py --name vehicle-attributes-recognition-barrier-0039 --precisions INT8 -o /home/workspace

In the udacity workspace, you should add a `-o` argument at the end.

You can verify the download of these models by navigating to: /home/workspace/intel, which includes subdirectories for each precision, with respective `.bin` and `.xml` for each model.
