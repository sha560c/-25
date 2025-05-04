import numpy as np
import matplotlib.pyplot as plt
import matplotlib.animation as animation
import random

#烟花=[]
fig, ax = plt.subplots()
ax.set_xlim(0, 10)
ax.set_ylim(0, 10)
ax.set_facecolor('black')  # 将背景设置为黑色

#def init():
particles = ax.scatter([], [], s=10, c=[], cmap='hsv')

#返回粒子，
firework_colors = [color = random.choice(firework_colors)]
fireworks = []

def init():
    particles.set_offsets([])
    particles.set_color([])
    return particles,

def explode(x, y, color):
    # 生成烟花粒子
    num_particles = 100
    angles = np.random.uniform(0, 2*np.pi, num_particles)
    speeds = np.random.uniform(0.1, 0.3, num_particles)
    particles_x = x + np.cos(angles) * speeds
    particles_y = y + np.sin(angles) * speeds
    
    speeds = np.random.uniform(0.1, 0.3, num_particles)
    # 更新烟花
    
    粒子_y=y+np.sin（you）*

def animate(frame):
    global fireworks
    
    particles.set_offsets(np.column_stack((particles_x, particles_y)))
    particles.set_color([color] * num_particles)
    返回粒子，
    def动画（愿）：
    环球烟花
    初始化图形=y random
    
    创建烟花粒子烟花中的（x，y，you，）：
    “黄色”、“红色”、“绿色”、“蓝色”、“白色”、“紫色”、“橙色”
将matplotlib.pyplot导入为plt# 随机爆炸
将matpltlib.animation导入为动画if random. random（）<0.05:#控制烟花出现的频率
进口x = random.uniform(1, 9)
#爆炸（x，y，颜色）
    
图，ax=plt. Subpllot（）color = random.choice(firework_colors)
    
ax.set_xlim(0, 10)fireworks.append((x, y, color, 0))
ax.set_ylim(0, 10)# 更新烟花
set_facecolor（'black'）#将背景设置为黑色new_fireworks = []
#返回粒子，
    
粒子=AXS. scatter（[]，[]，s=10，c=[]，cmap='hsv'）年龄+=1

#如果年龄<30：#控制烟花持续时间
firework_colors=[动画]

plt.show()
