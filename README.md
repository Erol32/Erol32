- 👋 Hi, I’m @Erol32
- 👀 I’m interested in Riding motorcylce and devoloping
- 🌱 I’m currently learning devoloping gmaes
- 💞️ I’m looking to collaborate on SC  
- 📫 How to reach me erolmuhammed660@gmail.com  

<!---
Erol32/Erol32 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
def draw_heart():
    for i in range(6, -7, -1):
        line = ""
        for j in range(-30, 30):
            x = j * 0.04
            y = -i * 0.1
            if ((x**2 + y**2 - 1)**3 - x**2 * y**3) <= 0:
                line += "*"
            else:
                line += " "
        print(line)

draw_heart()
