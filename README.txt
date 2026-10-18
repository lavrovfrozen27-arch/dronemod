Drone Mod (Fabric 1.21.4, client-side)
Сборка: установи JDK 21 и Gradle (или скопируй папку src + build.gradle/gradle.properties/settings.gradle
в шаблон https://github.com/FabricMC/fabric-example-mod, ветка 1.21), затем:  gradle build
Готовый .jar будет в build/libs/ (берёшь файл БЕЗ -sources).
Клавиши (все меняются в Настройки -> Управление -> Drone Mod):
 G - вкл/выкл дрон, WASD - полёт по взгляду, Space/Shift - вверх/вниз, Ctrl - ускорение, J - вкл/выкл авто-бан.
Команда при столкновении: /ban <ник> 30d 2.4  (меняется в DroneClient.BAN_ARGS)
