# 何ができるの？
・ルル君が撫でられたときに表情が変わるようになります  
・MMDをONにすると撫でられても表情が変わらなくなります  
・[まばたきシステム](https://github.com/Luke-514/Lulu_Mabataki)と互換性があります  
&emsp;<img src="image/VRChat_2024-09-28_18-09-15.214_1920x1080.png" width="40%" />  
  
# 注意事項など
・対応アバターはらすちんワークス様の[ルル (Lulu)](https://aoikarasu.booth.pm/items/4271776)です  
・MMDボタンを削除している場合は撫でられたときに表情が変わらない可能性があります  
・デフォルトでは自分で触れても反応しないようになっています  
&emsp;(ContactのAllow Selfにチェックを入れると、自分で触れた際に反応するようになります)  
・[ルル少年期（Lulu.juvenileVer)](https://aoikarasu.booth.pm/items/6101679)、[ルル（Ifの姿） (Lulu.AnotherVer)](https://aoikarasu.booth.pm/items/6544416)に導入する場合は、  
&emsp;Contactの位置(Position)と大きさ(Radius)を変更する必要があります  
&emsp;<img src="image/位置サイズ調整.png" width="30%" />  
### Ifルル参考値  
#### Head_Contact  
&emsp;Position：X=0 Y=0.116 Z=0  
&emsp;Radius&nbsp;&nbsp;：0.17  
#### Muzzle_Contact  
&emsp;Position：X=0 Y=0.05 Z=0.16  
&emsp;Radius&nbsp;&nbsp;：0.06  
  
### ルル少年期参考値  
#### Head_Contact  
&emsp;Position：X=0 Y=0.135 Z=0.021  
&emsp;Radius&nbsp;&nbsp;：0.17  
#### Muzzle_Contact  
&emsp;Position：X=0 Y=0.053 Z=0.178  
&emsp;Radius&nbsp;&nbsp;：0.06  
  
# 導入手順
1.&nbsp;[Modular Avatar](https://modular-avatar.nadena.dev/ja)をプロジェクトに追加します  
  
2.&nbsp;[Releases](https://github.com/Luke-514/Lulu_Nade/releases/latest)からLulu_Nade.unitypackageをダウンロードして、プロジェクトにインポートします  
  
3.&nbsp;Assets>Lulu_Nadeの中にある**Lulu_nade.prefab**をアバター直下に追加します  
  
4.&nbsp;Assets>Lulu_Nadeの中にある**Head_Contact.prefab**と**Muzzle_Contact.prefab**を  
&emsp;**Armature→Hips→Spine→Chest→Neck→Head**の中に追加します  
&emsp;<img src="image/Prefab配置.png" width="30%" />  
  
# 導入後の注意事項
・FaceEmoを使用されている場合は、Contact設定にHead_ContactとMuzzle_Contactを追加する必要があります  
&emsp;<img src="image/faceemo.png" width="30%" />  
・VRCQuestToolでQuest対応させる場合は、Contact Senders & Receivers to Keepに  
&emsp;Head_ContactとMuzzle_Contactを追加する必要があります  
&emsp;<img src="image/quest.png" width="30%" />  
  
# 参考
ケーキのPC情報集会所  
【VRChat】撫でられたら喜んじゃう！Contact機能を使ってみた！  
https://keiki002.com/vr/vrchat-contact/  
  
# 免責事項
本アセットの使用によって発生した、いかなる損害に対しても作者は一切の責任を負いません  
  
# 利用規約
本アセットの改変・二次配布を許可します  
(二次配布を行う際はクレジットに作者の名前を記載していただけると嬉しいです)  
  
# 作者
Luke514  
  
# Special Thanks
優希@白狼わんこ  
kruztouya  

# 関連アセット
・[まばたきシステム](https://github.com/Luke-514/Lulu_Mabataki)  
・[尻尾振りシステム](https://github.com/Luke-514/Lulu_Tail_Move)  
  
# 寄付
<a href="https://www.buymeacoffee.com/Luke514" target="_blank"><img src="https://cdn.buymeacoffee.com/buttons/v2/default-yellow.png" alt="Buy Me A Coffee" style="height: 60px !important;width: 217px !important;" ></a>
