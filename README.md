<!DOCTYPE html>
<html lang="pt-BR" translate="no">
<head>
    <meta charset="UTF-8">
    <link rel="icon" href="/assets-v2/favicon.ico">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="google" content="notranslate">
    <title>SIGA Pregão SPA</title>
    <style>
        .modal {
            z-index: 99999 !important;
        }

        .modal-backdrop {
            z-index: 10400 !important;
        }

        .daterangepicker {
            z-index: 999991 !important;
        }
    </style>
    <link rel="stylesheet" type="text/css" href="/assets-v2/css/daterangepicker.css"/>
    <link rel="stylesheet" href="/assets-v2/fontawesome/css/font-awesome.min.css"/>
    <link rel="stylesheet" href="/assets-v2/fontawesome-free-5.15.2/css/all.css"/>
    <link rel="stylesheet" href="/assets-v2/css/select2.min.css"/>
    <link rel="stylesheet" href="/assets-v2/css/multi-step-form.css"/>
    <link rel="stylesheet" href="/assets-v2/css/jquery.timepicker.min.css"/>
    <link rel="stylesheet" href="/assets-v2/js/datatable/datatables.min.css"/>
    <link rel="stylesheet" href="/assets-v2/plugins/malihu-custom-scrollbar/jquery.mCustomScrollbar.min.css"/>
    <link href="https://unpkg.com/tabulator-tables@5.3.4/dist/css/tabulator.min.css" rel="stylesheet">
  <script type="module" crossorigin src="/assets-v2/index-DV7Mse16.js"></script>
  <link rel="stylesheet" crossorigin href="/assets-v2/index-DCWCDBxP.css">
</head>
<body>
<div id="app"></div>

<script>var STONLY_WID = "ae35847c-879b-11eb-afd4-062882f67cfe";</script>
<script>
    !function (s, t, o, n, l, y, w, g) {
        s.StonlyWidget || ((w = s.StonlyWidget = function () {
            w._api ? w._api.apply(w, arguments) : w.queue.push(arguments)
        }).queue = [], (y = t.createElement(o)).async = !0,
            (g = new XMLHttpRequest).open("GET", n + "version?v=" + Date.now(), !0), g.onreadystatechange = function () {
            4 === g.readyState && (y.src = n + "stonly-widget.js?v=" + (200 === g.status ? g.responseText : Date.now()),
                (l = t.getElementsByTagName(o)[0]).parentNode.insertBefore(y, l))
        }, g.send())
    }(window, document, "script", "https://stonly.com/js/widget/v2/");
</script>
<!-- stonly-widget - copy into the head -->
<script>
    (function (s, t, o, n, l, y, _) {
        if (s.stonlyTrack) return;
        _ = s.stonlyTrack = function () {
            _._api ? _._api.apply(_, arguments) : _.queue.push(arguments);
        };
        _.queue = [];
        y = t.createElement(o);
        y.async = !0;
        y.src = n;
        l = t.getElementsByTagName(o)[0];
        l.parentNode.insertBefore(y, l);
    })(window, document, 'script', 'https://stonly.com/js/tracker/stn.js');
    stonlyTrack('init', STONLY_WID);
</script>

<script type="text/javascript" src="/assets-v2/js/jquery.min.js"></script>
<script type="text/javascript" src="/assets-v2/js/moment.min.js"></script>
<script type="text/javascript" src="/assets-v2/js/daterangepicker.min.js"></script>
<script type="text/javascript" src="/assets-v2/js/pdfobject.min.js"></script>
<script type="text/javascript" src="/assets-v2/js/bootbox.all.min.js"></script>
<script type="text/javascript" src="/assets-v2/js/select2.min.js"></script>
<script type="text/javascript" src="/assets-v2/js/select2-pt-BR.min.js"></script>
<script type="text/javascript" src="/assets-v2/js/multi-step-form.js"></script>
<script type="text/javascript" src="/assets-v2/js/sockjs.min.js"></script>
<script type="text/javascript" src="/assets-v2/js/stomp.min.js"></script>
<script type="text/javascript" src="https://www.gstatic.com/charts/loader.js"></script>
<script type="text/javascript" src="https://www.gstatic.com/charts/51/loader.js"></script>
<script src="https://cdn.jsdelivr.net/npm/marked/marked.min.js"></script>


<script src='https://cdn.jsdelivr.net/npm/fullcalendar@6.1.7/index.global.min.js'></script>
<script src='/assets-v2/plugins/fullcalendar-6.1.7/packages/core/locales-all.global.js'></script>
<script src='/assets-v2/plugins/fullcalendar-6.1.7/packages/core/locales/pt-br.global.min.js'></script>

<script src="/assets-v2/plugins/malihu-custom-scrollbar/js/minified/jquery.mCustomScrollbar.min.js"></script>
<script src="/assets-v2/plugins/malihu-custom-scrollbar/js/minified/jquery.mousewheel.min.js"></script>

<link rel="stylesheet" href="https://cdn.ckeditor.com/ckeditor5/44.3.0/ckeditor5.css">

<script src="/assets-v2/build/ckeditor.js"></script>
<!--<script src="https://cdn.ckeditor.com/ckeditor5/41.4.2/classic/ckeditor.js"></script>-->
<script src="/assets-v2/plugins/ckeditor5/pt-br.js"></script>

<!--<script src="https://cdn.ckeditor.com/ckeditor5/44.3.0/ckeditor5.umd.js"></script>-->
<!--<script src="https://cdn.ckeditor.com/ckeditor5/44.3.0/translations/pt-br.umd.js"></script>-->


<script src="/assets-v2/js/BigPicture.min.js"></script>
<script src="/assets-v2/js/venobox.min.js"></script>
<script src="/assets-v2/js/v-contextmenu@2.6.0_dist_index.js"></script>
<script src="https://cdnjs.cloudflare.com/ajax/libs/pdfobject/2.2.12/pdfobject.min.js"></script>
<script src="https://cdn.jsdelivr.net/npm/echarts@5.3.3/dist/echarts.min.js"></script>
<script src="https://unpkg.com/tabulator-tables@5.3.4/dist/js/tabulator.min.js"></script>
<script src="/assets-v2/js/readmore.min.js"></script>
<script src="/assets-v2/js/brmap.js"></script>
<script src="/assets-v2/js/jquery.timepicker.min.js"></script>
<script src="/assets-v2/js/datepicker/js/bootstrap-datepicker.min.js"></script>
<script src="/assets-v2/js/bootstrap-datepicker-1.9.0/locales/bootstrap-datepicker.pt-BR.min.js"></script>

<script src="/assets-v2/js/graficos/util.js"></script>
<script src="/assets-v2/js/graficos/pca-graficos.js"></script>
<script src="/assets-v2/js/graficos/atas-graficos.js"></script>
<script src="/assets-v2/js/jquery-ui.js"></script>
<script src="/assets-v2/js/datepicker-pt-BR.js"></script>
<script src="/assets-v2/js/dropzone.min.js"></script>
<script src="/assets-v2/js/jquery.mask.min.js"></script>
<script src="/assets-v2/js/datatable/datatables.min.js"></script>
<!--<script src="/assets-v2/js/jsrender.min.js"></script>-->
<!--<script src="/assets-v2/js/jsviews.min.js"></script>-->

<script src="/assets-v2/plugins/amcharts4/core.js"></script>
<script src="/assets-v2/plugins/amcharts4/charts.js"></script>
<script src="/assets-v2/plugins/amcharts4/themes/material.js"></script>
<script src="/assets-v2/plugins/amcharts4/themes/animated.js"></script>
<script src="/assets-v2/plugins/amcharts4/lang/pt_BR.js"></script>
<script src="/assets-v2/js/jquery.json-editor.min.js"></script>
<script src="/assets-v2/js/bignumber.min.js"></script>
<script src="https://unpkg.com/currency.js/dist/currency.min.js"></script>

<!--<script type="text/javascript" async src="https://d335luupugsy2.cloudfront.net/js/loader-scripts/b9ead298-a85b-44aa-b7a4-93ca3aac1b40-loader.js"></script>-->
<script src="//fast.appcues.com/84286.js"></script>


<script>
    google.charts.load('current', {
        'packages': ['corechart', 'controls', 'geochart', 'table'],
        'language': 'pt'
    });

    function abrirHistorico(el, tipo) {
        document.dispatchEvent(new CustomEvent("abrirhistorico", {
            detail: {
                el: el,
                tipo: tipo,
            },
        }));
    }

    function openlicitacao(id) {
        document.dispatchEvent(new CustomEvent("openlicitacao", {
            detail: {
                id: id,
            },
        }));
    }

    function novasugestao(s) {
        document.dispatchEvent(new CustomEvent("novasugestao", {
            detail: {
                s: s,
            },
        }));
    }

    function abrirHistoricoAta(el, tipo) {
        document.dispatchEvent(new CustomEvent("abrirHistoricoAta", {
            detail: {
                el: el,
                tipo: tipo,
            },
        }));
    }

    function abrirhistoricodoitem(id) {
        document.dispatchEvent(new CustomEvent("abrirhistoricodoitem", {
            detail: {
                id: id,
            },
        }));
    }


</script>


</body>
</html>
