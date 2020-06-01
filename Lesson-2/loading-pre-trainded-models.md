To access the Model Downloader, GO to: `cd /opt/intel/openvino/deployment_tools/tools/model_downloader`

Task 1 - Find the Right Models
Using the [Pre-Trained Model list](https://software.intel.com/en-us/openvino-toolkit/documentation/pretrained-models) , determine which models could accomplish the following tasks (there may be some room here in determining which model to download):

    Human Pose Estimation
      sudo ./downloader.py --name human-pose-estimation-0001 (all precision levels)
    Text Detection
      sudo ./downloader.py --name text-detection-0004 --precisions FP16
    Determining Car Type & Color
      sudo ./downloader.py --name text-detection-0004 --precisions FP16
