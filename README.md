Settings I've made

1. access jupyter notebook with Pycharm \n
**In order not to download large anaconda** \n
![image](https://github.com/user-attachments/assets/4decef65-f587-4de1-8748-fe9e05f0cf7a)
!pip install jupyter \n
open in browser # may wait a few minutes for pycharm to respond \n

2. Access kaggle with jupyter notebook \n
**Access directly, no need to download to local path** \n
get token at setting \n
create a new folder .kaggle at the python path \n
copy kaggle token json file to the path \n
!pip install kaggle \n
!kaggle datasets download -d waqi786/mental-health-and-technology-usage-dataset # path copied from kaggle dataset webpage \n
![image](https://github.com/user-attachments/assets/814556f6-2f46-4dd4-84ee-9144da766f5d)

3. unzip a file in jupyter notebook ( pycharm) \n
import zipfile  # basic python library, no need to install \n
with zipfile.ZipFile(file_name,'r') as zip_ref: \n
  zip_ref.extractall(file_folder_name) \n
