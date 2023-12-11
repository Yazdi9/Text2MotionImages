## Text2 Motion Images(Video) 

### Click on each gif to see the full motion

<table class="center">
      <tr >
      <td  style="border: none; text-align: center">Video/Prompt(word base)</td>
      <td  style="border: none; text-align: center">Video/Prompt(word base)</td>
      <td  style="border: none; text-align: center">Video/Prompt(word base)</td>
      <td  style="border: none; text-align: center">Video/Prompt(word base)</td>
      </tr>
      <tr>
      <td style="border: none"><img src="Results/0-1girl,-offshoulder,-light-smile,-shiny-skin-best-quality,-masterpiece,-photorealistic.gif"></td>
      <td style="border: none"><img src="Results/2-cut-tusuncub-walking-in-the-snow,-blurry,-looking-at-viewer,.gif"></td>
      <td style="border: none"><img src="Results/3-character-design,-cyberpunk-tusun-kitten-wearing-astronaut-suit,-sci-fic,-realistic.gif"></td>
      <td style="border: none"><img src="Results/2-best-quality,-masterpiece,-photorealistic,-1girl,-light-smile,-shirt-with-collars,.gif"></td>    
      </tr>
      <tr >
      <td  style="border: none; text-align: center">girl,-offshoulder,-light-smile,-shiny-skin-best-quality,-masterpiece,-photorealistic </td>
      <td  style="border: none; text-align: center">cut-tusuncub-walking-in-the-snow,-blurry,-looking-at-viewer</td>
      <td  style="border: none; text-align: center">character-design,-cyberpunk-tusun-kitten-wearing-astronaut-suit,-sci-fic,-realistic</td>
      <td  style="border: none; text-align: center">best-quality,-masterpiece,-photorealistic,-1girl,-light-smile,-shirt-with-collars</td>
      </tr>
      <tr >
      <td  style="border: none; text-align: center">Video/Prompt(Sentence base) </td>
      <td  style="border: none; text-align: center">Video/Prompt(Sentence base)</td>
      <td  style="border: none; text-align: center">Video/Prompt(Sentence base)</td>
      <td  style="border: none; text-align: center">Video/Prompt(Sentence base)</td>
      </tr>
       <td style="border: none"><img src="Results/ezgif.com-video-to-gif.gif"></td>
      <td style="border: none"><img src="Results/ezgif.com-video-to-gif (3).gif"></td>
      <td style="border: none"><img src="Results/ezgif.com-video-to-gif (1).gif"></td>
      <td style="border: none"><img src="Results/ezgif.com-video-to-gif (2).gif"></td>
      </tr>
       <tr >
      <td  style="border: none; text-align: center">The_astronaut_dances_in_futuristic..</td>
      <td  style="border: none; text-align: center">A_daring_man_performing_gravity-defying</td>
      <td  style="border: none; text-align: center">A_daring_man_is_scaling_a_treacherous..</td>
      <td  style="border: none; text-align: center">A_mighty_elephant_marches_steadily.</td>
      </tr>
</table>

## 🎆🎆Models..
  - Please download the MotionLoRA models (**74 MB per model**, available at [Google Drive](https://drive.google.com/drive/folders/1EqLC65eR1-W-sGD0Im7fkED6c8GkiNFI?usp=sharing) / [HuggingFace](https://huggingface.co/guoyww/animatediff) and save them to the `models/MotionLoRA` folder. Example:
  ```
  python -m scripts.animate --config configs/prompts/v2/5-RealisticVision-MotionLoRA.yaml
  ```

 `mm_sd_v15_v2.ckpt` was trained on larger resolution & batch size, and gains noticeable quality improvements. Check it out at [Google Drive](https://drive.google.com/drive/folders/1EqLC65eR1-W-sGD0Im7fkED6c8GkiNFI?usp=sharing) and use it with `configs/inference/inference-v2.yaml`. Example:
  ```
  python -m scripts.animate --config configs/prompts/v2/5-RealisticVision.yaml

  ```

## 🖨🖨Run 
```
python app.py
```
By default, the demo will run at `localhost:7860`.
<br>

  
