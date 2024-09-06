Settings I've made

1. access jupyter notebook with Pycharm
**In order not to download large anaconda**
![image](https://github.com/user-attachments/assets/4decef65-f587-4de1-8748-fe9e05f0cf7a)
!pip install jupyter
open in browser # may wait a few minutes for pycharm to respond

2. Access kaggle with jupyter notebook
**Access directly, no need to download to local path**
get token at setting
create a new folder .kaggle at the python path
copy kaggle token json file to the path
!pip install kaggle
!kaggle datasets download -d waqi786/mental-health-and-technology-usage-dataset # path copied from kaggle dataset webpage
![image](https://github.com/user-attachments/assets/814556f6-2f46-4dd4-84ee-9144da766f5d)

3. unzip a file in jupyter notebook ( pycharm)
import zipfile  # basic python library, no need to install
with zipfile.ZipFile(file_name,'r') as zip_ref:
  zip_ref.extractall(file_folder_name)
