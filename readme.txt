       Kesci--Я���û�Ԥ���������͸���Ԥ��   ����Ŀ¼

���л�����python2.7

����ѵ���������Ĵ��룺
gen_trainfeature1.py   --����train_related_feature1.csv����Ŀ¼data��
gen_trainfeature2.py   --����train_feature1.csv����dataĿ¼��
gen_trainfeature3.py   --����train_feature_add3.csv,  
gen_trainfeature4.py   --����train_feature_add4_1.csv����data/new-feature-6-22/Ŀ¼��

���ɲ��Լ������Ĵ��루��Ӧ�Ĳ��Լ���������
gen_testfeature1.py    --����
gen_testfeature2.py    --����
gen_testfeature3.py    --����
gen_testfeature4.py    --����

����ѵ�����Ͳ��Լ�����
feature_combine13.py   --����add_train13��add_test13�����dataĿ¼��
feature_combine15.py   --����train_newfeatures43.csv  �� test_newfeatures43.csv�����data/features6-18����   
gen_feature5.py        --����add_train5.csv��add_test5.csv����Ŀ¼  data/newfeature-5��
feature_make_1.py��feature_make_1_optimized.py��  --����train_ismaintype.csv��test_ismaintype.csv�����data/features6-18����
ע��feature_make_1.py �ⲿ�ִ���д��ʱ��û���ǵ��Ż������⣬���а����˴����������жϣ�������Ҫ���кܳ�ʱ�䡣�������������Ƕ��ⲿ�ִ���������Ż���
������Ϊfeature_make_1_optimized.py��ʵ��ʹ��ʱ�Ƽ����д��ļ����档
                              
###########################################################
�����������ɣ���������˳��
gen_trainfeature1.py   gen_testfeature1.py    
gen_trainfeature2.py   gen_testfeature2.py  
feature_combine13.py    
feature_combine15.py   
gen_trainfeature3.py   gen_testfeature3.py    
gen_trainfeature4.py   gen_testfeature4.py    
gen_feature5.py
feature_make_1.py
###########################################################

ģ��ѵ�����������Ԥ������
train_lgb.py
train_xgb.py

ģ���ںϴ��룺
linear_fusion.py   �����ںϣ���óɼ���
multiply_fusion.py  ����ں�

datasetĿ¼�´��ѵ�����Ͳ��Լ�����
dataĿ¼�´���������ɵ� ѵ�����Ͳ��Լ�����
fusion_dataĿ¼�´�Ž���ģ���ں�ǰ  xgboost��lightGBM���ɵ����з���Ԥ��ĸ���
��ߵ÷ֽ���ļ�Ϊ��linear_submission_0.2_0.8.csv �����fusion_dataĿ¼��


