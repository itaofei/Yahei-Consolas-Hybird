# YaHei Consolas Hybrid 1.12
For those who has chinese display issue use intellij idea in linux. 

## Auto installation

```
wget -qO- https://github.com/itaofei/YaHei-Consolas-Hybird/raw/master/install.sh | sudo sh
```

## Manual installation
+ download font.
```
git clone https://github.com/itaofei/YaHei-Consolas-Hybird.git
```

+ create dictionary /usr/share/fonts/truetype/YaHei\ Consolas\ Hybrid
```
sudo mkdir -p /usr/share/fonts/truetype/YaHei\ Consolas\ Hybrid
```

+ copy YaHei Consolas Hybrid 1.12.ttf there.
```
sudo cp YaHei\ Consolas\ Hybrid\ 1.12.ttf /usr/share/fonts/truetype/YaHei\ Consolas\ Hybrid
```

+ change privilege.
```
cd /usr/share/fonts/truetype/YaHei\ Consolas\ Hybrid
sudo chmod 644 YaHei\ Consolas\ Hybrid\ 1.12.ttf
```

+ start install font.
```
# make fonts.scale
sudo mkfontscale

# make fonts.dir
sudo mkfontdir

# make font cache
sudo fc-cache -fv
```
