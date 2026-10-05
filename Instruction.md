# 更新正式學生
python admin.py import-students student_data/group_class.csv

# 看目前權限
python admin.py list-students

# 學生換網路
python admin.py reset-ip student@example.com

# Student Key 遺失
python admin.py reset-key student@example.com

# 停權
python admin.py disable-student student@example.com

# 啟動
./run_server_from_keychain.sh