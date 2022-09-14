# lj_save
 Tool for encrypting/decrypting Lost Judgment saves.

Original decryption code from [here](https://gist.github.com/simontime/59661a189b20fc3517b20d8c9f329017) by simontime. I added proper checksum calculation and split the tool into two executables for easier usage.

Lost Judgment Key discovered by @jason098

## Usage

`lj_decrypt.exe data.sav` will output into `data.json`.

`lj_encrypt.exe data.json` will output into `data.sav`.

Alternatively you can just drag and drop the file onto the respective exe.
