# tms-docker-22
Найдите на Docker Hub образ, который вы хотите запустить на вашей
машине.
<img width="1409" height="103" alt="изображение" src="https://github.com/user-attachments/assets/e446bd4f-2e57-4b95-bebe-4d73dc74fcdc" />
Используя команду docker run, запустите контейнер на основе этого
образа. Добавьте флаги, чтобы установить имя контейнера,
перенаправить порты, установить переменные окружения и т.д.
Используйте команду docker ps, чтобы убедиться, что контейнер
запущен.
<img width="1416" height="166" alt="изображение" src="https://github.com/user-attachments/assets/30ee5a33-1c80-4a9d-ad5e-dcd80086b805" />
<img width="747" height="620" alt="изображение" src="https://github.com/user-attachments/assets/699c74d4-1416-45e1-8011-aa5ad925999c" />

Остановите контейнер, используя команду docker stop, и удалите его,
используя команду docker rm.
<img width="1044" height="154" alt="изображение" src="https://github.com/user-attachments/assets/96e9490e-c14e-413d-a151-2fb7145bffae" />

Используя команду docker images, выведите список всех образов,
установленных на вашем хосте.
<img width="1050" height="130" alt="изображение" src="https://github.com/user-attachments/assets/a0a02e4d-203b-46b2-b04a-00524c44de13" />

Используя команду docker inspect, выведите информацию о размере
каждого образа и его слоях. Найдите образы, которые занимают много
места на диске, и определите, какие слои образа занимают больше
всего места.
<img width="1817" height="249" alt="изображение" src="https://github.com/user-attachments/assets/be8979b5-bdb5-4563-9ec4-798bc5043ec6" />
<img width="1817" height="164" alt="изображение" src="https://github.com/user-attachments/assets/c310b43a-e682-470a-ab90-50128014b126" />

Если вы обнаружили образы, которые больше не нужны, удалите их,
используя команду docker rmi.
<img width="1143" height="170" alt="изображение" src="https://github.com/user-attachments/assets/732c2b4e-4fce-4e7e-bb51-8e69ce238e08" />

Используйте команду docker system prune для удаления ненужных
образов, контейнеров, томов и сетей, которые больше не используются
вашими приложениями.
<img width="985" height="452" alt="изображение" src="https://github.com/user-attachments/assets/07415094-0aac-4b65-8082-dc7fddb36b1b" />

После выполнения этих действий проверьте использование дискового
пространства на вашем хосте и убедитесь, что вы освободили
достаточно места.
<img width="897" height="182" alt="изображение" src="https://github.com/user-attachments/assets/a14d1f8e-df91-42b3-998d-88e4b847363b" />
