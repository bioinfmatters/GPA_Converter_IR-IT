# GPA_Converter_IR-IT
## Iran-Italy GPA Converter 
I asked chatGPT to tell me the formula of GPA Conversion from scale 20 (Iran) to scale 100 or 110 (Italy).
![image](https://github.com/bioinfmatters/GPA_Converter_IR-IT/assets/127447384/14786524-dfff-4503-8adb-1fad0ceef392)

and here is the function:
```python

def convert_grades():
    try:
        iranian_grade = float(grade_entry.get())
        scale = scale_var.get()
        if scale == '110':
            converted_grade = ((iranian_grade - 10) / 10) * 44 + 66
        else: #scale == '100'
            converted_grade = ((iranian_grade - 10) / 10) * 40 + 60
```
You can also download the app for windows users. Wish you luck.
