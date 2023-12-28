# RL_Proyecto

### Entrenamiento de agentes en entornos Atari.

#### ENTRENAMIENTO 

--> cd rl-baselines3-zo

--> python3 train.py --algo dqn --env Breakout-v4  -f logs/ --progress 

(para editar hiperparametros ir a hyperparams/dqn.yml o mirar train.py para pasar los argumentos por consola)

#### PROBAR MODELOS ENTRENADOS 

--> cd rl-baselines3-zo

-->python3 enjoy.py  --algo dqn  --env Breakout-v4 --n-timesteps 10000  --folder logs/



#### (Instalacion de requisitos)
--> pip install -r requirements.txt

