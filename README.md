# vina-env

AutoDock VinaやRDKitを用いた、計算化学・ドッキングシミュレーション用のConda環境です。

## 📦 含まれている主なライブラリ
* AutoDock Vina (`vina`)
* RDKit (`rdkit`)
* OpenBabel (`openbabel`)
* ADFR suite (`adfr-suite`)
* Meeko (`meeko`)
* Biopython / ProDy / NumPy / Pandas など

## 🚀 環境の構築方法（使い方）

このリポジトリの `environment.yaml` を使って、全く同じ環境を簡単に自分のPCに再現できます。

### 手順
1. リポジトリをダウンロード（クローン）します。
   ```bash
   git clone [https://github.com/MO0425/vina-env.git](https://github.com/MO0425/vina-env.git)
   cd vina-env
   ```

2. Condaを使って環境を構築します（環境名は `environment.yaml` 内の `name` フィールドで指定されたものになります。デフォルトでは vina です）。
   ```bash
   conda env create -f environment.yaml
   ```
   
3. 構築した環境を有効化します。
   ```bash
   conda activate vina
   ```