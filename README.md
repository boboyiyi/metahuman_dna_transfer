# metahuman_dna_transfer
Transfer the DNA of an existing MetaHuman to your custom avatar with **just a single command and no need of Maya!**

## Requirement

- ≥ win10 (Linux is also supported, feel free to contact me if you need)

## Usage

```
# e.g. Transfer Bernice's DNA to Ada
$ .\dna_transfer.exe .\assets\example\Bernice.dna .\assets\example\Ada Bernice2Ada.dna
```
- $1: Reference DNA file
- $2: Custom mesh path (make sure the up axis is "Y" and provide **head/left_eye/right_eye** at least, more mesh -> better result)
- $3: Transferred DNA file

## Examples

<table class="center">
  <tr style="font-weight: bolder;text-align:center;">
        <td width="37%">Ada</td>
        <td width="63%">Original Ada talking video</td>
  </tr>
  <tr>
    <td>
      <img src=assets/Ada.png>
    </td>
    <td >
     <video src="https://github.com/boboyiyi/metahuman_dna_transfer/blob/47635f5f35ed4ba662480adff32bbfbad5351bff/assets/Ada.mp4" controls preload></video>
    </td>
  </tr>
</table>

<table class="center">
  <tr style="font-weight: bolder;text-align:center;">
        <td width="37%">Bernice</td>
        <td width="63%">Transfer Bernice's DNA to Ada</td>
  </tr>
  <tr>
    <td>
      <img src=assets/Bernice.png>
    </td>
    <td >
     <video src="https://github.com/boboyiyi/metahuman_dna_transfer/blob/47635f5f35ed4ba662480adff32bbfbad5351bff/assets/Bernice2Ada.mp4" controls preload></video>
    </td>
  </tr>
</table>

<table class="center">
  <tr style="font-weight: bolder;text-align:center;">
        <td width="37%">Gavin</td>
        <td width="63%">Transfer Gavin's DNA to Ada</td>
  </tr>
  <tr>
    <td>
      <img src=assets/Gavin.png>
    </td>
    <td >
     <video src="https://github.com/boboyiyi/metahuman_dna_transfer/blob/47635f5f35ed4ba662480adff32bbfbad5351bff/assets/Gavin2Ada.mp44" controls preload></video>
    </td>
  </tr>
</table>

## Reference
- [MetaHuman-DNA-Calibration](https://github.com/EpicGames/MetaHuman-DNA-Calibration)