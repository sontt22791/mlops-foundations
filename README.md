# mlops-foundations
practical mlops

## cloud bash
xem file cloud-bash-essentials.md

## cloud computing
xem file cloud-computing.md

## optimization
greedy coin: https://github.com/noahgift/greedy_coin

Randomized Start with Greedy Path Solution for TSP (How can you travel to a list of cities and minimize the distance): https://github.com/noahgift/or

## data science doing
EDA covid: https://github.com/paiml/practical-mlops-book/blob/main/Data_Science_With_Covid.ipynb

housing price: https://github.com/noahgift/boston_housing_pickle

flask deploy: https://github.com/noahgift/flask-ml-azure-serverless

## azure
example project: https://github.com/noahgift/flask-ml-azure-serverless
1-clone
2-create and run new venv
3-make install
4-run app.py & su dung 1 terminal khac de ./make_predict.sh

tuy nhien minh test ca local va azure deu loi, do library sklearn (maybe)

## azure devops
phan nay chua test thu, huong dan trong sach con kha so sai, kho ma nho de ap dung
Use CI/CD to deploy a Python web: https://docs.microsoft.com/en-us/azure/devops/pipelines/ecosystems/python-webapp?view=azure-devops

Continuous Delivery with Azure Pipelines in Python: https://www.youtube.com/watch?v=3KF9DltYvZU

add lint: https://www.youtube.com/watch?v=TItOatTfAOc

## edge device (coral)
1. setup enviroment cho coral: cài đặt TPU, clone example project classification, tạo virtualenv python, install library python.
link: https://github.com/google-coral/tflite/tree/master/python/examples/classification
2. down pretrain model từ tfhub (vd https://tfhub.dev/tensorflow/coral-model/mobilenet_v2_1.0_224_quantized/1/default/1)
3. trong trường hợp model chưa đc compile để sử dụng cho TPU, có thể dùng convert của coral (chú ý model dùng để convert fai là tflite, và đã đc quantized)
có thể dùng docker để tạo enviroment dùng để convert nếu như k dùng linux (convert này yêu cầu os linux => tham khảo dockerfile ở https://github.com/paiml/practical-mlops-book/tree/main/chapter3)
