## 制作メモ

### コイル作成時に使用したツール
https://github.com/YugnatD/Kicad-NFC-Coil-Generator

main.pyで設定したパラメーター：

~~~
CAPACITANCE_CHIP = 45.92e-12 # 45.92 pF
RESONANT_FREQUENCY = 13.56e6 # 13.56 MHz

DESIGN_STYLES = "rectangular"
# DESIGN_STYLES = "spiral"

DEFAULT_MIN_LENGTH = 30
DEFAULT_MAX_LENGTH = 40
DEFAULT_STEP_LENGTH = 0.1

DEFAULT_MIN_TURNS = 6
DEFAULT_MAX_TURNS = 8
DEFAULT_STEP_TURNS = 1

DEFAULT_MIN_WIDTH = 0.5
DEFAULT_MAX_WIDTH = 0.7
DEFAULT_STEP_WIDTH = 0.1

DEFAULT_MIN_SPACING = 0.3
DEFAULT_MAX_SPACING = 0.5
DEFAULT_STEP_SPACING = 0.1
~~~



共振周波数：13.56MHz → C=45.92pF

$$f=\frac{1}{2\pi\sqrt{LC}}$$から計算

LED
https://akizukidenshi.com/catalog/g/g130070/

コンデンサ
https://akizukidenshi.com/catalog/g/g117481/

抵抗
https://akizukidenshi.com/catalog/g/g130343/

ぜんぶ1608サイズ．手はんだできそうなサイズ（たぶん）．無理ならトースターかホットプレートで焼く．

ロゴ・QRコードはKiCadのイメージコンバータでフットプリント化．
