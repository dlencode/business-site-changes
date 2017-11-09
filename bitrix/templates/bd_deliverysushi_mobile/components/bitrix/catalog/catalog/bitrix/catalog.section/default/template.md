This block of code:
```
$MiniPhoto = CFile::ResizeImageGet($arItem['PREVIEW_PICTURE']['ID'], array('width'=>'400', 'height'=>'400'), BX_RESIZE_IMAGE_EXACT, true);
```

Need to replace:
```
$MiniPhoto = CFile::ResizeImageGet($arItem['PREVIEW_PICTURE']['ID'], array('width'=>'520', 'height'=>'400'), BX_RESIZE_IMAGE_EXACT, true);
```
