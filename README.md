# Auxiliar
Auxilia a saber a posição do mause na tela
import time
import pyautogui # type: ignore

time.sleep(10)
print(pyautogui.position())

pyautogui.scroll(200)
