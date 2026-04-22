# Python Game Course

这是一套面向初中生的 Python 游戏编程课程课件，使用 Jupyter Notebook 进行教学。

课程目标不是只学语法，而是一步一步做出自己的小游戏，并逐渐形成编程思维。

## 课程内容

- `lesson01`：Python 入门，认识 `print()`
- `lesson02`：`input()`，让程序和玩家互动
- `lesson03`：变量，保存角色信息
- `lesson04`：数字运算，生命值和金币变化
- `lesson05`：字符串，生成故事文本
- `lesson06`：`if` 判断，做剧情选择
- `lesson07`：阶段小项目《神秘洞穴大冒险》
- `lesson08`：列表，制作背包系统
- `lesson09`：`for` 循环，批量展示物品
- `lesson10`：`while` 循环，制作游戏主菜单
- `lesson11`：随机数，做随机奖励和猜数字游戏
- `lesson12`：字典，制作角色属性系统
- `lesson13`：函数，开始整理重复代码
- `lesson14`：函数的参数，让函数接收外部信息
- `lesson15`：函数的返回值，让函数把结果交回来
- `lesson16`：f-string，让游戏文字输出更好看
- `lesson17`：列表套字典，管理多个角色和物品
- `lesson18`：try/except，防止程序因玩家乱输入崩溃

## 目录说明

- 每节课放在一个单独文件夹中
- 每个文件夹内主要是 `.ipynb` 课件
- 学生上课时直接打开对应 Notebook 即可

## 老师更新课件的方法

建议老师把这个项目放到 GitHub 仓库中，之后每次新增或修改课件时：

1. 修改本地课件文件
2. 提交到 GitHub
3. 学生在自己的电脑上同步更新

如果你已经安装 Git，可以使用下面这组基本命令：

```bash
git add .
git commit -m "更新第14到16课课件"
git push
```

## 学生第一次获取课件

学生第一次使用时，可以把整个仓库下载到自己的电脑。

如果已经安装 Git，可以使用：

```bash
git clone 你的仓库地址
```

如果没有安装 Git，也可以直接在 GitHub 页面点击：

`Code -> Download ZIP`

## 学生以后同步更新

如果学生已经是通过 Git 获取的课件，之后只需要进入项目文件夹，然后执行：

```bash
git pull
```

这条命令的意思就是：把老师在 GitHub 上的新内容同步到自己的电脑。

## 对学生的建议

- 不要直接修改老师原始课件，可以另外保存自己的练习版本
- 如果改动很多，建议把自己的作业单独放进 `student_work` 文件夹
- 每次上课前先同步一次最新课件

## 建议的教学使用方式

- 老师讲解时使用原始课件
- 学生跟着在课件中实操
- 课后可以把自己的练习另存为新文件

例如：

- `lesson05_strings_story.ipynb` 是老师版本
- `lesson05_strings_story_student_张三.ipynb` 是学生版本

## 后续建议

后面可以继续补充：

- `student_work/` 学生作业目录
- `requirements.txt` 环境说明
- `course_map.md` 总课程路线图
- `teacher_notes/` 教师讲课备注
