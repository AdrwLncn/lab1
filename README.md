Лабораторная работа #1
Тема: "Основы работы с Unity"

Отчет по лабораторной работе #1 выполнил(а):
- Матвеев Андрей Александрович
- РИ-300022
Отметка о выполнении заданий (заполняется студентом):

| Задание | Выполнение | Баллы |
| ------ | ------ | ------ |
| Задание 1 | * | 60 |
| Задание 2 | * | 20 |
| Задание 3 | * | 20 |

знак "*" - задание выполнено; знак "#" - задание не выполнено;

Работу проверили:
- к.т.н., доцент Денисов Д.В.
- к.э.н., доцент Панов М.А.
- ст. преп., Фадеев В.О.

Структура отчета

- Данные о работе: название работы, фио, группа, выполненные задания.
- Цель работы.
- Задание 1.
- Код реализации выполнения задания. Визуализация результатов выполнения (если применимо).
- Задание 2.
- Код реализации выполнения задания. Визуализация результатов выполнения (если применимо).
- Задание 3.
- Код реализации выполнения задания. Визуализация результатов выполнения (если применимо).
- Выводы.
- ✨Magic ✨

## Цель работы
Ознакомиться с основами Unity

## Задание 1

![image](https://user-images.githubusercontent.com/70385106/213868422-0dbeb226-69c6-443a-ae50-bdb1438b3f1e.png)
![image](https://user-images.githubusercontent.com/70385106/213868464-0bde0398-13db-4f4a-9d2a-419f03881719.png)
![image](https://user-images.githubusercontent.com/70385106/213869179-9250384a-b66c-4230-80cd-ca1e4377b7b9.png)
![image](https://user-images.githubusercontent.com/70385106/213869198-6867d168-11af-43e9-9dd2-7bf7fcc19688.png)

```C#
using System.Collections;
using System.Collections.Generic;
using UnityEngine;

public class CheckColider : MonoBehaviour
{
    // Start is called before the first frame update
    void Start()
    {
        
    }

    // Update is called once per frame
    void Update()
    {
        
    }

    private void OnTriggerEnter(Collider other) {
        Debug.Log("Произошло столкновение с" + other.gameObject.name);
        other.GetComponent<Renderer>().material.SetColor("_Color", Color.green);
    }

    private void OnTriggerExit(Collider other) {
        Debug.Log("Завершено столкновение с" + other.gameObject.name);
        other.GetComponent<Renderer>().material.SetColor("_Color", Color.red);
    }
}
```
## Задание 2
![image](https://user-images.githubusercontent.com/70385106/213870267-a5fdc0bf-2a91-478f-9558-02fe857b71c0.png)
![image](https://user-images.githubusercontent.com/70385106/213870301-2a7ac095-4ec8-4d50-8bb7-69c257dff531.png)
![image](https://user-images.githubusercontent.com/70385106/213870681-8f012a78-70bd-40cb-b269-2101ff1e7ad4.png)

## Задание 3


## Выводы



