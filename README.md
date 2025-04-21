# PTB-XL-MLC
Multilabel classification benchmark for ptb-xl dataset. 

O dataset é composto por diversos exames de homens e mulheres. 

https://physionet.org/content/ptb-xl/1.0.3/ 

Iremos realizar a classificacao das Superclasses. 
Total de classes no dataset. 
Classes 
Records	Superclass	Description
9514	| NORM	| Normal ECG
5469	| MI	  | Myocardial Infarction
5235	| STTC	| ST/T Change
4898	| CD	  | Conduction Disturbance
2649	| HYP	  | Hypertrophy

As amostras foram geradas considerando a frequencia de 500Hz e fazendo após isso o downsample para 100 Hz. Com isso, foram geradas 21k imagens separadas em 21 repositorios. 
ptbxl
├── ptbxl_database.csv
├── scp_statements.csv
├── records100
│   ├── 00000
│   │   ├── 00001_lr.dat
│   │   ├── 00001_lr.hea
│   │   ├── ...
│   │   ├── 00999_lr.dat
│   │   └── 00999_lr.hea
│   ├── ...

Os arquivos csv, dizem respeito ao label correspondente e ao caminho do arquivo .hea de cada uma das imagens. 




# Generating our data. 
## 1 - Download dataset. 
## 2 - Geracao das imagens (image-kit)
## 3 - Geracao csv Multilabel

# Workflow Training model
## 1 - Load dataset. 
## 2 - Filtering images. 
## 3 - Build Model. 
## 4 - Train loop. 

# Results
