## Statova Nadejda IA2404, Informatica Aplicata, номер 24, продвинутый уровень

## Скриншоты базового уровня

| Подсеть   | Зона доступности | Диапазон      | Первый и последний доступные IP | Количество доступных IP |
|-----------|------------------|---------------|--------------------------------|-------------------------|
| public-a  | eu-central-1a    | 10.24.0.0/24  | 10.24.0.4 – 10.24.0.254       | 251                     |
| public-b  | eu-central-1b    | 10.24.1.0/24  | 10.24.1.4 – 10.24.1.254       | 251                     |
| private-a | eu-central-1a    | 10.24.10.0/24 | 10.24.10.4 – 10.24.10.254     | 251                     |
| private-b | eu-central-1b    | 10.24.11.0/24 | 10.24.11.4 – 10.24.11.254     | 251                     |


#### Задание 3: маршруты public-rt и private-rt и их связи с подсетями.

![screen1](images/public-routes.png)
*Маршруты public-rt*

![2](images/public-rt-subnet-association.png)
*Связи public-rt с подсетями*

![3](images/private-routes.png)
*Маршруты private-rt*

![4](images/private-routes-subnemt-associations.png)
*Связи private-rt с подсетями*

#### Задание 4: входящие правила трёх Security Group

![5](images/bastion-sec-group.png)
*Входящие правила timecapsule-dev-bastion-sg*

![6](images/db-sec-group.png)
*Входящие правила timecapsule-dev-db-sg*

![7](images/db-sec-group.png)
*Входящие правила timecapsule-dev-web-sg*

#### Задание 5: страница web-server в браузере.

![8](images/login-app-using-elastic-ip.png)
*Страница web-server* 

#### Задание 6: вывод curl https://checkip.amazonaws.com на db-server, маршрут в состоянии Blackhole и список NAT gateways, где шлюз в состоянии Deleted

![9](images/checkip-amazonaws-comand.png)
*Вывод curl https://checkip.amazonaws.com на db-server*

![10](images/blackhole-status.png)
*Маршрут в состоянии Blackhole*

![11](images/nat-gateway-deleted.png)
*NAT gateways, где шлюз в состоянии Deleted*

#### Задание 7: вывод psql с web-server, проверка порта 5432 с web-server и bastion, результат эксперимента с Network ACL, список ресурсов в Tag Editor с тегом Project = timecapsule

![11](images/database-access-ex7.png)
*Вывод psql с web-server*

![12](images/network-acl-ssh-bastion-timeout.png)
*dev-bastion timeout при изменении inbound rules*

![13](images/network-acl-web-unavailable.png)
*dev-web unavailable при изменении inbound rules*

![14](images/resource-groups-tag-editor.png)
*Список ресурсов в Tag Editor*

## Скриншоты продвинутого уровня:

### Задание 9: приложение в браузере по Elastic IP.

![15](images/elastic-ip-address.png)
*Созданный Elastic IP*

![16](images/login-app-using-elastic-ip.png)
*Приложение в браузере по Elastic IP*

#### Задание 11: запись db в зоне и вывод dig с app-server и dig или nslookup с вашего компьютера.

![18](images/dig-short-db-timecapsule-internal.png)
*Вывод dig с app-server*

![19](images/nslookup-from-device.png)
*Вывод nslookup с компьютера*

![20](images/postgres-setup.png)
*Настройка postgres*

![21](images/route53.png)
*Hosted zone*

#### Задание 12: вывод psql -f, ответ /health и капсулы из ЛР2 на странице.

![22](images/download-data-via-private-network.png)
*Вывод psql -f*

![23](images/web-site.png)
*ответ /health*

#### Задание 13: 

![24](images/db-stop-health-result.png)
*/health при остановленной базе*

![25](images/dnf-update-result.png)
*вывод sudo dnf -y update на db-server*

![26](images/temporary-nat-gateway-info.png)
*NAT Gateway info*

![25](images/architecture-lab02.drawio.png)
*Схема работы*


