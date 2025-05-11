# Interface 2023年7月号 特集「ゼロから作るOS」

## 概要
本リポジトリは、CQ出版(株) Interface 2023年7月号の特集「ゼロから作るOS」の勉強記録用のリポジトリです。

## ライセンスについて

本プログラムはMITライセンスの下でオープンソースとして公開されています。</br>
詳細は <https://github.com/ytoyoyama/trykernel> をご確認ください。

## ディレクトリ概要
- include</br>
定義ファイル
- boot</br>
起動処理ソースコード
- kernel</br>
OS本体
- device</br>
デバドラ
- application</br>
アプリケーションソースコード
- linker</br>
リンカ・スクリプト・ファイル

## 開発環境
- IDE
  - Eclipse IDE for Embedded C/C++ Developers
  - <https://www.eclipse.org/downloads/packages/release/2024-12/r>

- ビルドツール
  - xPack GNU Arm Embedded GCC
    - ARM Cortex-M/M0/M3/M4/M7などのマイコン向けに開発されたC/C++クロスコンパイラ（GNUベース）
    - arm-none-eabi-gcc（C/C++コンパイラ）
    - <https://xpack-dev-tools.github.io/arm-none-eabi-gcc-xpack/>

  - xPack Windows Build Tools
    - windows用の構築ツール
    - <https://xpack-dev-tools.github.io/windows-build-tools-xpack/>

- デバック環境
  - OpenOCD（Open On-Chip Debugger）
    - JTAGやSWD経由でデバッグ・書き込み・制御するためのオープンソースのツール
    - <https://github.com/ciniml/debug-tools-builder/releases>

  - デバックプローブ
    - (公式) Raspberry Pi Debug Probe
    - <https://www.raspberrypi.com/documentation/microcontrollers/debug-probe.html>
