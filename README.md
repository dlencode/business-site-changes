## Backups of business site

#### Navigation:
- desktop
  - [font](./bitrix/templates/bd_deliverysushi/font/)
  - [images](./bitrix/templates/bd_deliverysushi/images/)
  - [header.php](./bitrix/templates/bd_deliverysushi/header.md)
  - [template_styles.css](./bitrix/templates/bd_deliverysushi/template_styles.css)
- mobile
  - [font](./bitrix/templates/bd_deliverysushi_mobile/font/)
  - [images](./bitrix/templates/bd_deliverysushi_mobile/images/)
  - [header.php](./bitrix/templates/bd_deliverysushi_mobile/header.md)
  - [template_styles.css](./bitrix/templates/bd_deliverysushi_mobile/template_styles.css)
- crm
  - static
    - [css/style.css](./crm/static/css/style.css)
    - [font](./crm/static/font/)
  - print
    - [css/style.css](./crm/static/print/css/style.css)
    - [fonts](./crm/static/print/fonts/)
- upload
  - [dlencode](./upload/dlencode/)



#### Breadcrumb

In file 'components/bitrix/breadcrumb/bread/template.php' replace the part of code:
```
$strReturn = '<a href="#" class="breadcrumb-toggle"><img src="'.SITE_TEMPLATE_PATH.'/images/breadcrumb.png"></a>
              <div class="breadcrumb-path-container">
	              <a href="#" class="close">&times;</a>';
```
to:
```
$strReturn = '<a href="#" class="breadcrumb-toggle"><img src="/upload/dlencode/elements/link.svg"></a>
              <div class="breadcrumb-path-container">
	              <a href="#" class="close">&times;</a>';
```
