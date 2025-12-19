Orientações:

Para rodar o newman: "newman run 'Books_API_collection.json' -e 'Books_API_environment.json' -r htmlextra"

API Pública: https://fakerestapi.azurewebsites.net/index.html
Esta API não persiste dados, com isso, as requests falharam e não foi possível realizar a criação, alteração e consulta por ID dos Books. No entanto, apliquei os testes positivos e negativos e capturei evidências dos erros para adicionar no bug report que criei.
