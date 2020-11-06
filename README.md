## Accuracy of each experiments
### 1. PlainNet
|Network-Num|BS|LR|Aver ACC|0ACC|1ACC|2ACC|3ACC|4ACC|5ACC|6ACC|
|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
|PlainNet-1|16|0.0001|<b>91.33%</b>|83.10%|92.86%|91.55%|98.61%|88.73%|100.00%|84.06%|
|PlainNet-2|16|0.0001|<b>86.09%</b>|78.87%|95.71%|76.06%|97.22%|87.32%|97.22%|69.57%|
|PlainNet-3|16|0.0001|<b>86.69%</b>|77.46%|100.00%|84.51%|94.44%|84.51%|100.00%|65.22%|
|PlainNet-4|16|0.0001|<b>91.33%</b>|84.51%|94.29%|97.18%|97.22%|78.87%|100.00%|86.96%|
|PlainNet-5|16|0.0001|<b>88.71%</b>|88.73%|87.14%|98.59%|97.22%|81.69%|91.67%|75.36%|
|PlainNet-6|16|0.0001|<b>85.28%</b>|95.77%|72.86%|97.18%|94.44%|81.69%|77.78%|76.81%|
|PlainNet-7|16|0.0001|<b>88.51%</b>|80.28%|90.00%|84.51%|98.61%|80.28%|100.00%|85.51%|
|~~PlainNet-8~~|~~16~~|~~0.0001~~|~~66.94%~~|~~66.20%~~|~~32.86%~~|~~100.00%~~|~~91.67%~~|~~38.03%~~|~~80.56%~~|~~57.97%~~|
|PlainNet-9|16|0.0001|<b>81.25%</b>|100.00%|57.14%|95.77%|98.61%|54.93%|88.89%|72.46%|
|PlainNet-10|16|0.0001|<b>91.94%</b>|98.59%|91.43%|92.96%|97.22%|83.10%|97.22%|82.61%|

|Network-Num|BS|LR|Aver ACC|0ACC|1ACC|2ACC|3ACC|4ACC|5ACC|6ACC|
|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
|PlainNet-SAM-1|16|0.0001|<b>87.70%</b>|76.06%|97.14%|94.37%|97.22%|74.65%|100.00%|73.91%|
|PlainNet-SAM-2|16|0.0001|<b>87.10%</b>|91.55%|88.57%|98.59%|97.22%|54.93%|97.22%|81.16%|
|PlainNet-SAM-3|16|0.0001|<b>90.93%</b>|91.55%|94.29%|88.73%|100.00%|88.73%|100.00%|72.46%|
|PlainNet-SAM-4|16|0.0001|<b>84.88%</b>|73.24%|98.57%|87.32%|94.44%|77.46%|97.22%|65.22%|
|PlainNet-SAM-5|16|0.0001|<b>87.90%</b>|84.51%|84.29%|100.00%|93.06%|74.65%|91.67%|86.96%|
|PlainNet-SAM-6|16|0.0001|<b>87.50%</b>|85.92%|95.71%|85.92%|93.06%|87.32%|98.61%|65.22%|
|PlainNet-SAM-7|16|0.0001|<b>89.31%</b>|83.10%|97.14%|87.32%|100.00%|80.28%|100.00%|76.81%|
|PlainNet-SAM-8|16|0.0001|<b>90.12%</b>|95.77%|97.14%|91.55%|94.44%|88.73%|97.22%|65.22%|
|PlainNet-SAM-9|16|0.0001|<b>90.73%</b>|95.77%|90.00%|98.59%|97.22%|85.92%|97.22%|69.57%|
|PlainNet-SAM-10|16|0.0001|<b>90.73%</b>|98.59%|88.57%|91.55%|93.06%|80.28%|97.22%|85.51%|


|network|aver acc|
|:---:|:---:|
|PlainNet|87.90%|
|PlainNet-SAM|88.69%|


### 2. ResNet
|Network-Num|BS|LR|Aver ACC|0ACC|1ACC|2ACC|3ACC|4ACC|5ACC|6ACC|
|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
|ResNet-1|16|0.0001|<b>83.06%</b>|73.24%|75.71%|97.18%|83.33%|85.92%|87.50%|78.26%|
|ResNet-2|16|0.0001|<b>84.27%</b>|78.87%|87.14%|84.51%|94.44%|91.55%|100.0%|52.17%|
|ResNet-3|16|0.0001|<b>77.02%</b>|46.48%|85.714%|61.97%|98.61%|92.958%|98.61%|53.62%|
|ResNet-4|16|0.0001|<b>78.63%</b>|83.10%|84.286%|98.59%|97.22%|57.75%|90.28%|37.68%|
|ResNet-5|16|0.0001|<b>83.87%</b>|63.39%|94.29%|88.73%|94.44%|60.56%|97.22%|88.41%|
|ResNet-6|16|0.0001|<b>81.45%</b>|70.42%|98.57%|64.79%|95.83%|88.73%|98.61%|52.17%|
|ResNet-7|16|0.0001|<b>86.90%</b>|88.73%|81.43%|98.59%|97.22%|70.42%|94.44%|76.81%|
|ResNet-8|16|0.0001|<b>81.65%</b>|85.92%|90.00%|84.51%|87.50%|92.96%|98.61%|30.43%|
|ResNet-9|16|0.0001|<b>89.31%</b>|85.92%|92.86%|95.77%|95.83%|78.87%|97.22%|78.26%|
|ResNet-10|16|0.0001|<b>87.30%</b>|85.92%|95.71%|94.37%|94.44%|87.32%|100.0%|52.17%|

|Network-Num|BS|LR|Aver ACC|0ACC|1ACC|2ACC|3ACC|4ACC|5ACC|6ACC|
|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
|ResNet-SAM-1|16|0.0001|<b>90.73%</b>|94.37%|90.00%|97.18%|98.61%|76.06%|97.22%|81.16%|
|ResNet-SAM-2|16|0.0001|<b>85.08%</b>|80.28%|94.29%|80.28%|100.0%|70.42%|100.0%|69.57%|
|ResNet-SAM-3|16|0.0001|<b>83.67%</b>|85.92%|85.71%|88.73%|100.0%|59.15%|95.83%|69.56%|
|ResNet-SAM-4|16|0.0001|<b>88.10%</b>|98.59%|94.29%|91.55%|98.61%|85.91%|97.22%|49.28%|
|ResNet-SAM-5|16|0.0001|<b>88.10%</b>|84.51%|87.14%|88.73%|100.0%|94.37%|100.0%|60.87%|
|ResNet-SAM-6|16|0.0001|<b>84.88%</b>|87.32%|81.43%|76.06%|90.28%|97.18%|88.89%|72.47%|
|ResNet-SAM-7|16|0.0001|<b>87.90%</b>|90.14%|92.86%|98.59%|98.61%|71.83%|95.83%|66.67%|
|ResNet-SAM-8|16|0.0001|<b>87.90%</b>|80.28%|95.71%|84.51%|95.83%|83.10%|97.22%|78.26%|
|ResNet-SAM-9|16|0.0001|<b>86.69%</b>|84.51%|85.71%|91.55%|98.61%|70.42%|95.83%|79.71%|
|ResNet-SAM-10|16|0.0001|<b>81.048%</b>|73.24%|78.57%|95.77%|98.61%|50.70%|95.83%|73.91%|


|network|aver acc|
|:---:|:---:|
|3DResNet|83.35%|
|3DResNet-SAM|86.41%|

### 3. InceptionNet
|Network-Num|BS|LR|Aver ACC|0ACC|1ACC|2ACC|3ACC|4ACC|5ACC|6ACC|
|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
|Inception-1|16|0.0001|<b>84.48%</b>|67.61%|84.29%|91.55%|97.22%|78.87%|97.22%|73.91%|
|Inception-2|16|0.0001|<b>87.90%</b>|83.10%|88.57%|95.77%|95.83%|90.14%|91.67%|69.57%|
|Inception-3|16|0.0001|<b>86.90%</b>|87.32%|92.86%|88.73%|100.00%|85.92%|90.28%|62.32%|
|Inception-4|16|0.0001|<b>87.30%</b>|80.28%|94.29%|91.55%|97.22%|77.46%|97.22%|72.46%|
|Inception-5|16|0.0001|<b>80.65%</b>|61.97%|100.00%|84.51%|94.44%|73.24%|91.67%|57.97%|
|Inception-6|16|0.0001|<b>83.27%</b>|83.10%|88.57%|80.28%|98.61%|85.92%|91.67%|53.62%|
|Inception-7|16|0.0001|<b>86.49%</b>|92.96%|85.71%|85.92%|100.00%|69.01%|97.22%|73.91%|
|Inception-8|16|0.0001|<b>83.47%</b>|81.69%|95.71%|83.10%|100.00%|78.87%|95.83%|47.83%|
|Inception-9|16|0.0001|<b>86.90%</b>|84.51%|100.00%|91.55%|95.83%|76.06%|94.44%|65.22%|
|Inception-10|16|0.0001|<b>83.47%</b>|87.32%|97.14%|74.65%|98.61%|78.87%|91.67%|55.07%|

|Network-Num|BS|LR|Aver ACC|0ACC|1ACC|2ACC|3ACC|4ACC|5ACC|6ACC|
|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
|Inception-SAM-1|16|0.0001|<b>88.51%</b>|85.92%|97.14%|90.14%|100.00%|71.83%|95.83%|78.26%|
|Inception-SAM-2|16|0.0001|<b>80.04%</b>|70.42%|91.43%|64.79%|97.22%|91.55%|98.61%|44.93%|
|Inception-SAM-3|16|0.0001|<b>86.09%</b>|88.73%|92.86%|87.32%|95.83%|61.97%|95.83%|79.71%|
|Inception-SAM-4|16|0.0001|<b>87.70%</b>|83.10%|94.29%|90.14%|95.83%|84.51%|93.06%|72.46%|
|Inception-SAM-5|16|0.0001|<b>85.28%</b>|80.28%|78.57%|94.37%|95.83%|78.87%|93.06%|75.36%|
|Inception-SAM-6|16|0.0001|<b>88.91%</b>|90.14%|85.71%|88.73%|95.83%|85.92%|93.06%|82.61%|
|Inception-SAM-7|16|0.0001|<b>86.90%</b>|81.69%|80.00%|94.37%|98.61%|76.06%|97.22%|79.71%|
|Inception-SAM-8|16|0.0001|<b>87.50%</b>|84.51%|90.00%|94.37%|94.44%|87.32%|100.00%|60.87%|
|Inception-SAM-9|16|0.0001|<b>85.89%</b>|77.46%|90.00%|92.96%|95.83%|76.06%|97.22%|71.01%|
|Inception-SAM-10|16|0.0001|<b>85.89%</b>|83.10%|94.29%|94.37%|98.61%|69.01%|88.89%|72.46%|

|network|aver acc|
|:---:|:---:|
|Inception|85.08%|
|Inception-SAM|86.07%|
