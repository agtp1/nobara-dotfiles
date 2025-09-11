RICE 1:
- EXTENSIONS:
  
![imagen](https://github.com/user-attachments/assets/63fb87b3-e7be-4552-977b-52762bba3408)

![imagen](https://github.com/user-attachments/assets/00d4a8df-15b6-4678-bd16-1062c5652d91)

![imagen](https://github.com/user-attachments/assets/c4e66e7d-e6c9-4ca9-85a8-5bab314ddd8d)



- THEME-CURSOR-ICONS
  
![imagen](https://github.com/user-attachments/assets/054c220f-288f-4ae6-a41f-30c04451c371)



![Captura desde 2025-05-10 01-37-56](https://github.com/user-attachments/assets/2b7b2b98-9685-4c51-8876-34b4bb2deba4)
![Imagen pegada](https://github.com/user-attachments/assets/a4b178be-c076-43ca-9eb7-7a99dbf638f3)
![Captura desde 2025-05-10 01-45-11](https://github.com/user-attachments/assets/e3c8e452-e846-486b-b3af-93e231301a1e)
![Captura desde 2025-05-10 01-39-42](https://github.com/user-attachments/assets/97e28df1-b906-426c-8472-778964906de2)
![Captura desde 2025-05-10 01-39-04](https://github.com/user-attachments/assets/635ce3fc-15d3-4dd0-bc5e-7f951440e495)
![Captura desde 2025-05-10 01-38-17](https://github.com/user-attachments/assets/4bbd282a-48a7-45fc-8d08-b8ad41e6cc9f)


RICE 2:
- EXTENSIONS

<img width="619" height="967" alt="imagen" src="https://github.com/user-attachments/assets/05a095cd-79da-4a17-9814-33bb62889aef" />

<img width="607" height="416" alt="imagen" src="https://github.com/user-attachments/assets/f00ca0f4-88f6-409c-a60a-3df2a3ac9f2f" />

BLUR MY SHELL:

<img width="638" height="582" alt="imagen" src="https://github.com/user-attachments/assets/4709b062-6419-47bf-9abc-137ec80007dd" />

<img width="638" height="582" alt="imagen" src="https://github.com/user-attachments/assets/021402f7-296c-4b18-9792-01f118c13df3" />

GNOME SHELL: https://mega.nz/folder/0ApTGZpD#NpFymCIXiFpw2oS-3z5DQA

ICONS: Tela circle

Spotify: Spicetify with text theme catppuccin mocha

Kitty: Colors with gogh (catppuccin mocha)

Fast fetch config:
//    ______           __  ______      __ 
//   / ____/___ ______/ /_/ ____/___ _/ /_
//  / /_  / __ `/ ___/ __/ /   / __ `/ __/
// / __/ / /_/ (__  ) /_/ /___/ /_/ / /_  
///_/    \__,_/____/\__/\____/\__,_/\__/  
//  https://github.com/m3tozz/FastCat
{
    "$schema": "https://github.com/fastfetch-cli/fastfetch/raw/dev/doc/json_schema.json",
    "logo": {

"type": "kitty",

"source": "/home/agt_p1/.config/fastfetch/saslogoo.png", // o cualquier ruta válida

"width": 35,

"height": 17,

"padding": {

"top": 4

}

  

},
    "modules": [
        "break",
        {
            "type": "custom",
            "format": "\u001b[94m┌──────────────────────Hardware──────────────────────┐"
        },
        {
            "type": "host",
            "key": " PC",
            "keyColor": "green"
        },
        {
            "type": "cpu",
            "key": "│ ├",
            "showPeCoreCount": true,
            "keyColor": "green"
        },
        {
            "type": "gpu",
            "key": "│ ├󰍛",
            "keyColor": "green"
        },
        {
            "type": "memory",
            "key": "│ ├󰍛",
            "keyColor": "green"
        },
        {
            "type": "disk",
            "key": "└ └",
            "keyColor": "green"
        },
        {
            "type": "custom",
            "format": "\u001b[94m└────────────────────────────────────────────────────┘"
        },
        "break",
        {
            "type": "custom",
            "format": "\u001b[94m┌──────────────────────Software──────────────────────┐"
        },
        {
            "type": "os",
            "key": " OS",
            "keyColor": "yellow"
        },
        {
            "type": "kernel",
            "key": "│ ├",
            "keyColor": "yellow"
        },
        {
            "type": "packages",
            "key": "│ ├󰏖",
            "keyColor": "yellow"
        },
        {
            "type": "shell",
            "key": "└ └",
            "keyColor": "yellow"
        },
        "break",
        {
            "type": "custom",
            "format": "\u001b[94m┌──────────────────────Desktop───────────────────────┐"
        },
        {
            "type": "de",
            "key": " DE",
            "keyColor": "blue"
        },
        {
            "type": "lm",
            "key": "│ ├",
            "keyColor": "blue"
        },
        {
            "type": "wm",
            "key": "│ ├",
            "keyColor": "blue"
        },
        {
            "type": "wmtheme",
            "key": "│ ├󰉼",
            "keyColor": "blue"
        },
        {
            "type": "gpu",
            "key": "└ └󰍛",
            "format": "{3}",
            "keyColor": "blue"
        },
        {
            "type": "custom",
            "format": "\u001b[94m└────────────────────────────────────────────────────┘"
        },
        "break",
        {
            "type": "custom",
            "format": "\u001b[94m┌────────────────────Uptime / Age────────────────────┐"
        },
        {
            "type": "command",
            "key": "  OS Age ",
            "keyColor": "magenta",
            "text": "birth_install=$(stat -c %W /); current=$(date +%s); time_progression=$((current - birth_install)); days_difference=$((time_progression / 86400)); echo $days_difference days"
        },
        {
            "type": "uptime",
            "key": "  Uptime ",
            "keyColor": "magenta"
        },
        {
            "type": "custom",
            "format": "\u001b[94m└────────────────────────────────────────────────────┘"
        },
        "break"
    ]
}

Kitty conf:

cursor                #eebf37
selection_background  #6f6a4e
selection_foreground #1e1c44
font_family MesloLGS NF Bold
font_size 12.0
hide_window_decorations yes
include theme.conf
background_opacity 0.8	


# Added by Gogh
include colors.conf

Discord: Better discord with custom css:

/* mocha */
@import url("https://catppuccin.github.io/discord/dist/catppuccin-mocha.theme.css");

<img width="1043" height="703" alt="imagen" src="https://github.com/user-attachments/assets/3bc47ab6-1cb9-4ade-9615-9a1657ff007d" />


Zen Browser: With catppuccin colors:

Copy the .css in this rute(if you install with flatpak): https://github.com/catppuccin/zen-browser?tab=readme-ov-file
/home/agt_p1/.var/app/app.zen_browser.zen/.zen/your_user (release)/chrome

And search 

<img width="204" height="74" alt="imagen" src="https://github.com/user-attachments/assets/70008dd7-1717-4a18-98ab-3306e9e6585e" />

<img width="1037" height="307" alt="imagen" src="https://github.com/user-attachments/assets/95d0e966-322f-4b99-9e8d-b03c260025b1" />

toolkit.legacyUserProfileCustomizations.stylesheets  (put true)

<img width="1691" height="133" alt="imagen" src="https://github.com/user-attachments/assets/ec16c9ac-ce88-4d06-87ab-2a4c56a3ec1b" />

/home/agt_p1/Documentos/SO LOFII/Captura desde 2025-09-11 22-21-39.png

/home/agt_p1/Documentos/SO LOFII/Captura desde 2025-09-11 22-33-13.png

/home/agt_p1/Documentos/SO LOFII/Captura desde 2025-09-11 22-35-12.png

/home/agt_p1/Documentos/SO LOFII/Captura desde 2025-09-11 22-35-44.png

/home/agt_p1/Documentos/SO LOFII/Captura desde 2025-09-11 22-36-04.png

/home/agt_p1/Documentos/SO LOFII/Captura desde 2025-09-11 22-36-20.png

/home/agt_p1/Documentos/SO LOFII/Captura desde 2025-09-11 22-36-46.png

