�������� ������ (������) ����� "�������� �������� � �������"

����:

ML: sklearn, pandas, numpy API: flask ������: � kaggle - https://www.kaggle.com/jsphyg/weather-dataset-rattle-package

������: ������������� ����� �� ��������� ����, ������ ������ ������������� �� ������� ���������� RainTomorrow .�������� �������������

������������ ��������:
'MinTemp',
'MaxTemp',
'Rainfall', 
'Evaporation'
'WindGustSpeed'
'WindSpeed9am',
'WindSpeed3pm',
'Humidity9am',
'Humidity3pm',
'Pressure9am',
'Pressure3pm',
'Cloud9am',
'Cloud3pm',
'Temp9am',
'Temp3pm',
'Location', 
'WindGustDir',
'WindDir9am',
'WindDir3pm',
'RainToday',
'RainTomorrow'

������: XGBClassifier

### ��������� ����������� � ������� �����

����� //app/models/ ��������:
1) weather_forecast.ipynb - ���������������� ����. ������ ������
2) Pyplene_class.ipynb - ������� �������. 
3) pipeline.dill  - ����������� ������ ������������� ������

����� //app/ ��������:
1) run_server.ipynb - ������ ������� ��� ��������� �������� flask
2) ������� � �������.ipynb - ��������� ������ ��������.
3) x_test.csv � y_test.csv. ������� ������ ��� �������.
