# emf2pdf
Convert emf image to pdf image

## Usage
### Install python packages
```bash
pip install -r requirements.txt
```

### Install libreoffice
```bash
sudo apt-get install libreoffice
```

### Execute
This will generate a `tmp/` folder and a pdf image in the image's directory
```bash
python3 emf2pdf.py <img_fname>
```

### Alias
Add the following line in `~/.bashrc` for easy execution
```
alias emf2pdf='python3 <python_fpath>/emf2pdf.py'
```
Execute in terminal
```
emf2pdf <image_fname>
```