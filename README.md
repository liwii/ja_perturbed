# 日本語文法誤りデータセット
[CC-100](https://data.statmt.org/cc-100/)の日本語データから抽出した日本語文と、[小川耀一朗、山本和英(2020) 日本語文法誤り訂正における誤り傾向を考慮した擬似誤り生成](https://www.anlp.jp/proceedings/annual_meeting/2020/pdf_dir/F2-3.pdf)の DirectNoise(ja) によって生成された擬似誤り文からなる、21198対のデータセットです。

## Method
擬似誤り文生成に必要な文章の係り受け分析や文節分解には[ginza](https://github.com/megagonlabs/ginza)を用いました。

## Files
- `ja_perturbed.csv`
生成されたデータセットです。`original`に抽出された元の文、`perturbed`に生成された擬似誤り文が記載されています。

## License
This datataset is distributed under the [MIT](https://opensource.org/license/mit/) license.