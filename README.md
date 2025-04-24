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
