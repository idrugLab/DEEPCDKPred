Datasets of CDK are in fold named "data".

Models of CDK we have trained are in fold named "model_save".
The version of PyTorch should above 1.6 when loading these trained models.

How to predict new molecules using trained models? For example, to predict several molecules saved in a CSV file named "pred.csv" on the CDK1 model, use this command:
python predict.py --predict_path pred.csv --model_path model_save/hyper-cdk1/model.pt --result_path result.csv

