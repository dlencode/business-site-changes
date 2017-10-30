This block of code:
```
<? if ($APPLICATION->GetCurPage(true) == SITE_DIR.'index.php'): ?><?else:?><a href="<?=SITE_DIR?>"><?endif?>
  <img src="/upload/dlencode/logotype.svg">
<? if ($APPLICATION->GetCurPage(true) == SITE_DIR.'index.php'): ?><?else:?></a><?endif?>
```

Need to replace into:
```
<div class="logo">
  ...
</div>
```
