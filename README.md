# ActiveMQ 를 알아가며

필자는 ActiveMQ를 알아가기 위해 ActiveMQ에 대해 공부하였다.
MQ는 Message Queue의 약자로, 데이터의 주고 받는 방식이 Message를 이용한 방식이다.
한 프로세스(또는 프로그램 인스턴스)가 Message를 MQ서버 MOM(Message Oriented Middleware)에 보내게 되면
지정된 Queue에 메세지가 쌓이고, 이를 다른 프로세스에서 지정된 Queue에 있는 메세지를 한 개 씩 받을 수 있다.

이를 실행한 결과이다. (Postman 사용)

![image](https://github.com/HINU0622/ActiveMQProject/assets/80612949/e8698204-91e1-42e2-b358-98cf117e071e)
사진에 보이진 않지만, Lee-jae-jin-queue라는 Queue로 Message를 보냄.

![image](https://github.com/HINU0622/ActiveMQProject/assets/80612949/510e7014-91b3-4af9-b540-cfb108620a4f)
Lee-jae-jin-queue에 1개의 Message가 쌓인 것을 볼 수 있음.

![image](https://github.com/HINU0622/ActiveMQProject/assets/80612949/ec753104-c26c-47be-bf3e-b0ae97f3170f)
그리고 다른 곳에서 이를 받음.

![image](https://github.com/HINU0622/ActiveMQProject/assets/80612949/bf48ec0e-e7fd-4918-a987-f3e3bcd43798)
Queue에서 정삭적으로 Message가 빠져나간 것을 알 수 있음.

# 이 글을 마치며

이를 통해서 MQ에 대해 이해할 수 있었고, MQ는 어디에 쓰이는지, 어떤 방식으로 동작 하는지에 대해 조금이나마 더 알 수 있었다.
