import tkinter as tk

# --- functions ---

def text_change():
    global phase_index
    global phase_string

    phase_tuple = ("Ready Phase", "Evolution Phase", "Battle Phase", "Point Phase")
    phase_string = phase_tuple[phase_index%4]

    phase_index += 1

    print("changed to:", phase_string)

    #btn['text'] = text
    btn.config(text=phase_string)

def text_print():
    print("current:", text)

# --- main ---

phase_index = 0

root = tk.Tk()

w = tk.Label(root, text=phase_index)
w.grid(row=1, column=1)
w.config(text=phase_index)

btn = tk.Button(text="Game Preparation", command=text_change, width=20, height=3)
btn.grid(row=2, column=1)

root.mainloop()
