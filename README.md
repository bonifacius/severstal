## ���������� � �������:

��������� �����������: git clone

-��������� � ����� � �������� ������� ����� ��������� ������� ����������� ���������: python -m venv test-django

-���������� ���������: source test-django/bin/activate

-������������� ����������� ������: pip install -r requirements.txt

-������ �������� ��: python manage.py migrate

-���������: python manage.py runserver

************************************************************************
## ����� ��� �����:
*************************************************************************
### ���������� �����:

### 1. �������� ������ ����� ����� ������.
### 2. ��������
   

    -����������� �������� Feedback �� ����������� ����� �� ���� email

   -��� gmail:

        -������� � ���� ����� � ��������� � "���������� google ���������"

        -�������� �� ������� ������������

        -����������� ���������� ������������� ��������������

        -����������� �������, ��� �� �������� ��������

        -�������� ���������� � ����������, ��� ������� ����� ������� ������ ����������. �� ��������������� ������ �������� "������"

        -����� �� �������� ������. ��������� ��� ���� ����-������



   -����� � settings.py � ����� ��������:

        EMAIL_BACKEND = 'django.core.mail.backends.smtp.EmailBackend'
        EMAIL_HOST = 'smtp.gmail.com'
        EMAIL_USE_TLS = True
        EMAIL_PORT = 587
        EMAIL_HOST_USER = '���� �����'
        EMAIL_HOST_PASSWORD = '������ ������� �� ������ ��� ��������'

    � � views.py �������� email � ������ post ������ FeedBackView(View):
    #send_mail(f'�� {name} | {subject}', message, from_email, ['need put email'])
   
### 3. ����� �� ������� � �� �����
   
    � navbar ������ �������� � ��������� �� �������� ������ � �����������
*************************
### 4. ����������� �������������
   
    -���� ������������ ����������� �� ������� ��� ������������ � navbar.
        
    -�������������� ������������� ����� ����� �� �������� ����� "�����". 
    
    -���� �� �����������, ������������ �����������, ���� ������ "�����������"
************************* 
### 5. �������� ������ ���������
    
    -���� � �������� �� ������� ������ ������ "���������", �� ��������� �� �������� �� �������.
   
    -������������ ��������:
   
        -�������� ������
   
        -���� �����������, ����� �������� �����������
   
        -���� ���, ������������ �������������� ��� ������������������
   
        -������ �������� ���� � ��������� 5 ������.
 *************************  
### 6. ��������� ��������� �� ����� 6 ������ �� ��������.
   