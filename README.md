# Nuvoladatepickercalendar
Es una versión editada del Bootstrap DateTimePicker 4, cambio del template mas sofisticado, para mayor info refiérase a Bootstrap DateTimePicker 4.
# Simple Ejemplo para inicializarlo 
```html
<div class="container">
            <div class="row">
                <div class='col-sm-12'>
                    <div class="form-group">
                        <div class='input-group date' >
                            <input id='datetimepicker1' type='text' class="form-control" />

                        </div>
                    </div>
                </div>
                <script type="text/javascript">
                    $(function () {
                        $('#datetimepicker1').nuvoladatepicker({
                            locale:"es"
                        });
                    });
                </script>
            </div>
        </div>
```
# Requerimientos 
- JQUERY
- BOOTSTRAP 
- MOMENT
- BOOTSTRAP-DATIMEPICKER
- FONTAWESOME
```html
<script src="bootstrap/js/jquery.js"></script>
<script src="bootstrap/js/bootstrap.js"></script>
<script src="moment/min/moment-with-locales.js"></script>
<script src="js/bootstrap-datetimepicker.js"></script>
<link rel="stylesheet" href="bootstrap/css/bootstrap.css">
<link rel="stylesheet" href="css/bootstrap-datetimepicker.css">
<link rel="stylesheet" href="font-awesome/css/font-awesome.css">

```

Para mayor información sobre requerimientos  y funcionalidades refierase a 
[Datetimepicker for Bootstrap 4](http://eonasdan.github.io/bootstrap-datetimepicker/)
