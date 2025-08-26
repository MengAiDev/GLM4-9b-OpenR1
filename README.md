# GLM4-9b-OpenR1
This is the usage of GLM4-9b-OpenR1

- Model on modelscope: https://modelscope.cn/models/MengAiDev/GLM4-OpenR1
- We use dataset: https://huggingface.co/datasets/open-r1/OpenR1-Math-220k

To inference, run: 
```bash
pip install -r requirements.txt
modelscope download MengAiDev/GLM4-OpenR1 --local_dir GLM4-OpenR1
python inference.py
```

- If you want to train from scatch, please vist: https://openi.pcl.ac.cn/MengAiDev/OpenZero
- See this: https://openi.pcl.ac.cn/MengAiDev/OpenZero/grampus/train-job/691727
