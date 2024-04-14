# 🚀 Machine Learning na Prática no Azure ML

##  Passo a passo de um modelo de previsão para aluguel de bicicletas 🚴🚴‍♀️:

#### 1. Foi definido algumas configurações do projeto e a descrição do experimento
![Parte 1](imagens/Etapa2.png)

---

#### 2. O tipo de tarefa é regressão
![Parte 1](imagens/EtapaRegressao.png)

---

#### 3. Continuação das configurações e definições
![Parte 1](imagens/Etapa3.png)

---

#### 4. Foi selecionado a opção de arquivos da web
![Parte 1](imagens/Etapa4.png)

---

#### 5. URL informada no tutorial
![Parte 1](imagens/Etapa5.png)

---

#### 6. Definição do cabeçalho
![Parte 1](imagens/Etapa6.png)

---


#### 7. Configurações de tarefas
![Parte 1](imagens/Etapa8.png)

---

#### 8. Definição da opção limites
![Parte 1](imagens/Etapa9.png)

---

#### 9. Configuração em computação
![Parte 1](imagens/Etapa10.png)

---

#### 10. Status Concluído
![Parte 1](imagens/Concluido.png)

---

#### 11. Pelo menu lateral selecionei a opção pontos de extremidade e usei o json  abaixo:

```
{
  "input_data": {
    "data": [
       {
         "day": 1,
         "mnth": 1,   
         "year": 2022,
         "season": 2,
         "holiday": 0,
         "weekday": 1,
         "workingday": 1,
         "weathersit": 2, 
         "temp": 0.3, 
         "atemp": 0.3,
         "hum": 0.3,
         "windspeed": 0.3 
       }
     ]
  }
}
```

---

#### 12. A previsão gerada foi: 361.95


