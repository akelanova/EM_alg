# EM_alg
Expectation-maximization (алгоритм кластеризации).
-----
Основная идея.
Данные в каждом кластере подчиняются нормальному закону распределению, поэтому для каждого кластера можно высчитать математическое ожидание и дисперсию, при которых функция правдоподобия (вероятность принадлежности объектов кластеру) максимальна. 
Мы предполагаем, что любой объект принадлежит ко всем кластерам, но с разной вероятностью. Задача заключаться в «подгонке» совокупности распределений к данным, а затем в определении вероятностей принадлежности объекта к каждому кластеру. Объект должен быть отнесен к тому кластеру, для которого данная вероятность выше. 
