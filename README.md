# python31090
Afterclass 05/08/2022 - Coderhouse


Para agregar los archivos estáticos:
1. Ir al settings.py y configurar STATICFILES_DIRS
2. Crear la carpeta static en la CARPETA RAIZ del proyecto (BASE_DIR)
3. En los templates donde lo van a usar agregar {% load static %}
4. En cada lugar donde van a usar agregar entre "{% static ' ' %}" --> Por ejemplo: <link href="{% static 'css/styles.css' %}" rel="stylesheet" />
