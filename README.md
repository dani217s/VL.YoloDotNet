# VL.YoloDotNet

- [ ] Is a VL wrapper for YoloDotNet: https://github.com/NickSwardh/YoloDotNet
- [ ] It implements YOLOv8 and YOLOv10 for real-time Object Detection, Classification, OBB Detection, Segmentation, Pose Estimation in images and videos.
- [ ] DirectML is used as the GPU acceleration provider
- [ ] More documentation on Ultralytics YOLOv8: https://docs.ultralytics.com/models/yolov8/

For use with vvvv, the visual live-programming environment for .NET: http://visualprogramming.net

# VVVV Gamma Compatibility

Due to a problem loading the ONNX DLL, VVVV Gamma 6.7.148 or later is required.
To use with Gamma 6.6, you must copy the ONNX DLLs to the Gamma installation folder.

# Export Yolo models to ONNX
All models must be exported to ONNX format. [How to export to ONNX format](https://docs.ultralytics.com/modes/export/#usage-examples).\
The ONNX-models included in this repo are from Ultralytics s-series (small). https://docs.ultralytics.com/models.

## Getting started
- Install as [described here](https://thegraybook.vvvv.org/reference/hde/managing-nugets.html) via commandline:

    `nuget install VL.YoloDotNet -pre`

- Usage examples and more information are included in the pack and can be found via the [Help Browser](https://thegraybook.vvvv.org/reference/hde/findinghelp.html)

## Credits
Based on YoloDotNet: https://github.com/NickSwardh/YoloDotNet



