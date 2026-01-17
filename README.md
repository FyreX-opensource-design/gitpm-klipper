klipper 3d printer firmware gitpm repo

get gitpm via this command:
```bash
wget https://raw.githubusercontent.com/FyreX-opensource-design/gitpm/refs/heads/main/gitpm.py && mkdir -p ~/.config/gitpm && wget -P ~/.config/gitpm/ https://raw.githubusercontent.com/FyreX-opensource-design/gitpm/refs/heads/main/repos-default.conf && chmod +x ./gitpm.py && ./gitpm.py install gitpm
```

then add the repo.conf
```bash
wget -P ~/.config/gitpm/ https://raw.githubusercontent.com/FyreX-opensource-design/gitpm-klipper/refs/heads/main/repos-klipper.conf
```
