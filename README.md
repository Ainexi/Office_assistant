# Office_assistant

-- 环境搭建
-- Anaconda 创建虚拟环境
conda create -n office_assistant python=3.8
conda activate office_assistant


-- 依赖
# 核心依赖
pip install torch==1.13.1+cpu -f https://download.pytorch.org/whl/torch_stable.html
pip install transformers==4.28.1 flask==2.2.3 pandas==1.5.3 scikit-learn==1.2.2

# 开发工具
pip install jupyterlab==3.6.1 ipython==8.12.0 black==23.3.0

# 生成requirements.txt
pip freeze > requirements.txt

-- 注意事项
因为bert模块下载连接不上，所有需要自己下载模型到本地运行 网站https://hf-mirror.com/google-bert/bert-base-chinese/tree/main
下载bert-base-chinese放入代码model，修改路径可以使用


