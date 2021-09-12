# ASobakin_microservices
# docker-2 HMW
Что сделано?
– настроен pre-commit для работы с новым репозиторием
– выполнено задание со "*": на основе анализа различий в выводе команды `docker inspect` для образа и контейнера, объяснение добавлено в файл "dockermonolith/docker-1.log");<br />
– создан Docker host в Yandex Cloud
– через `docker-machine create ...; eval $(docker-machine env docker-host)` локальное окружение настроено для работы с удаленным хостом
– в директории "dockermonolith/" создан Dockerfile и др. файлы, указанные в ДЗ
– локально запущен контейнер, созданный из образа, загруженного в Docker Hub