AnimateToAnchor
===============
平滑定位到锚点

‘   jQuery(document).ready(function ($) {
            $("a").click(function() {
                $("html, body").animate({
                    scrollTop: $($(this).attr("href")).offset().top + "px"
                }, {
                    duration: 300,
                    easing: "swing"
                });
                return false;
            });
        });
’

