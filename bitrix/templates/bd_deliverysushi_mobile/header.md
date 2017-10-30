This block of code:
```
<div class="title">
    <img src="/upload/dlencode/logotype.svg">
    <span></span>
</div>
```

Need to replace after:
```
<div class="header"><a href="#menu"></a>
<?if($APPLICATION->GetCurPage(false) === '/'): ?>
...
```
