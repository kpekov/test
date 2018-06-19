# test

```xml
<add name="UpdateService" type="Intelmet.SteelTrace.Machine.UpdateService, Intelmet.SteelTrace.Machine.UpdateService.dll">
  <configuration>
    <IP>192.168.160.55</IP>
    <Port>21</Port>
    <CheckInterval>5</CheckInterval>
    <AppType>iros</AppType>
    <Mode>manual</Mode>
  </configuration>
</add>
```

Parameter name | Description
--- | ---:
IP | Адрес сервера обновлений
Port | Порт сервера обновлений
CheckInterval | Интервал проверки обновлений в секундах (для режима auto)
AppType | Тип обновления (iros, iroshmi)
Mode | Режим обновления (auto, manual)
