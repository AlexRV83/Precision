# Отчёт о тестировании <Precision>

## Краткое описание

<15.07.2021> - <15.07.2021> было проведено <Функциональное тестирование> 
приложения <Precision>.

На тестирование затрачено: <1ч>

В результате тестирования выявлены следующие дефекты:
* [не корректная сумма бонуса новым клиентам](https://github.com/AlexRV83/Precision/issues/1)



## Описание процесса тестирования

В процессе тестирования использовались следующие артефакты*:
* [Test case](https://github.com/netology-code/javaqa-homeworks/tree/master/programming)




В качестве тестовых данных использовались данные:
* <public class Main {
  public static void main(String[] args) {
    double regularBonus = 0.3;
    double specialBonus = 0.6;
    double totalBonus = regularBonus + specialBonus;
    System.out.println(totalBonus);
  }
}>



Тестирование производилось в следующем окружении:
* <Windows 7 Домашняя базовая 64 -разрядная>
* <Android 10 QSBS30.62-19-17-6>
* <jdk-11.0.11.9-hotspot>
