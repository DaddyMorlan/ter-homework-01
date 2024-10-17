# Задание 1
пункт 1:

![](https://github.com/DaddyMorlan/ter-homework-01/blob/main/terraform-1/check%203.png)

пункт 2:

![](https://github.com/DaddyMorlan/ter-homework-01/blob/main/terraform-1/1.2.png)

пункт 3:

![](https://github.com/DaddyMorlan/ter-homework-01/blob/main/terraform-1/1.3.png)

пункт 4:

24 строка нет имени у recource, только тип

29 строка имя должно начинаться с буквы

31 строка лишнее _FAKE так как такого имени нет + большая T в resulT

![](https://github.com/DaddyMorlan/ter-homework-01/blob/main/terraform-1/1.4%20code.png)

![](https://github.com/DaddyMorlan/ter-homework-01/blob/main/terraform-1/1.4%20validate.png)

пункт 5:

![](https://github.com/DaddyMorlan/ter-homework-01/blob/main/terraform-1/1.5%20apply.png)

![](https://github.com/DaddyMorlan/ter-homework-01/blob/main/terraform-1/1.5%20ps.png)

пункт 6:

![](https://github.com/DaddyMorlan/ter-homework-01/blob/main/terraform-1/6%20code.png)

![](https://github.com/DaddyMorlan/ter-homework-01/blob/main/terraform-1/6%20approve.png)

![]([https://github.com/DaddyMorlan/ter-homework-01/blob/main/terraform-1/1.6%20ps.png](https://github.com/DaddyMorlan/ter-homework-01/blob/main/terraform-1/6%20ps.png))

Данный ключ опасен тем, что команда применяется без дополнительного подтверждения, а значит не предостерегает от непреднамеренных изменений

Ключ может пригодиться для автоматизации развертывания, например, в CI/CD пайплайне или каком-либо скрипте, а также для тестовых сред, которые часто подвергаются изменениям

пункт 7:

![](https://github.com/DaddyMorlan/ter-homework-01/blob/main/terraform-1/1.7%20destroy.png)

![](https://github.com/DaddyMorlan/ter-homework-01/blob/main/terraform-1/1.7%20tfstate.png)

пункт 8:

![](https://github.com/DaddyMorlan/ter-homework-01/blob/main/terraform-1/1.8%20code.png)

![](https://github.com/DaddyMorlan/ter-homework-01/blob/main/terraform-1/1.8%20docs.png)

keep_locally = true указывает, что image нужно оставить при destroy
