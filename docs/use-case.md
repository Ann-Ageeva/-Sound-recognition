Сценарий использования
1. На вход системы приходит несколько звуковых дорожек формата wav. 
2. Система обрабатывает звуковые дорожки с помощью разложения в ряд Фурье, который в последствии преобразуется в спектрограмму. Она подается на вход нейтронной сети, которая вычисляет вероятность присутствия дрона, в случае его присутствия направление определяется алгоритмом №2. 
3. На выходе мы должны получить вероятность присутствия дрона. В случае его обнаружения определить примерное направление. 