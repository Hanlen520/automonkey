1.��װpython3.6
  ����python��������
  path ���� C:\Users\zhangzhao\AppData\Local\Programs\Python\Python36
            C:\Users\zhangzhao\AppData\Local\Programs\Python\Python36\Scripts
2.��װpycharm�����ڿ��� ���ԣ���ʹ�ÿ��Թ���
  ��pycharm������(google)

3.��װpy��
  1)pip install lxml
  2)pip install requests
  3)pip install selenium
  4)pip install appium-python-client
  5)pip install pyyaml
  6)pip install xlsxwriter
  7)pip install wheel
down http://www.lfd.uci.edu/~gohlke/pythonlibs/#lxml
scipy-0.18.1-cp34-cp34m-win_amd64.whl
numpy-1.11.3+mkl-cp34-cp34m-win_amd64.whl
pyparsing-2.1.10-py2.py3-none-any.whl
python_dateutil-2.6.0-py2.py3-none-any.whl
pytz-2016.10-py2.py3-none-any.whl
matplotlib-2.0.0rc2-cp34-cp34m-win_amd64.whl
pip install xxx.whl
   8)easy_install Pillow

4.����androidsdk 
  ����$ANDROID_HOME ��������
  ANDROID_HOME ��Ϊ D:\android-sdk

5.�������µ�automonkey

6.���ذ�װnodejs

7.���ذ�װappium
  ����appiumdriver.py��startappiumdriver��װĿ¼
�� cmd = 'c:\\program files xxx'

8.��װjdk,���û�������
JAVA_HOME C:\Program Files\Java\jdk1.8.0_121
CLASSPATH C:\Program Files\Java\jdk1.8.0_121\lib\dt.jar;C:\Program Files\Java\jdk1.8.0_121\lib\tools.jar
PATH ���� C:\Program Files\Java\jdk1.8.0_121\bin

9.����appium-doctor���appium���л���
C:\Users\zhangzhao>appium-doctor
Running Android Checks
? ANDROID_HOME is set to "D:\android-sdk"
? JAVA_HOME is set to "C:\Program Files\Java\jdk1.8.0_121."
? ADB exists at D:\android-sdk\platform-tools\adb.exe
? Android exists at D:\android-sdk\tools\android.bat
? Emulator exists at D:\android-sdk\tools\emulator.exe
? Android Checks were successful.
? All Checks were successful

���У�
ִ��adb devices ��ȡuuid
����automonkeyĿ¼
python monkey.py -a conf\pandalive.apk -c conf\panda.yml -p android -i X2P0215518002631 -u 4723
-a apk·��
-c ���������ļ�
-p ƽ̨android/ios
-i �豸uuid
-u appium��ʼ�˿ں�