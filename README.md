ㅤㅤㅤㅤㅤㅤㅤㅤㅤㅤㅤㅤㅤㅤㅤㅤㅤㅤ𝐗𝐈𝐈𝐈.
<img width="1812" height="368" alt="Untitled255_20260106154737" src="https://github.com/user-attachments/assets/93199764-0ae1-4666-997a-7980f7e72ac9" />


ㅤㅤㅤㅤㅤㅤㅤㅤㅤㅤㅤㅤㅤㅤㅤ❝ See, sunshine? ㅤㅤㅤㅤㅤㅤㅤㅤㅤㅤㅤㅤㅤㅤㅤㅤㅤㅤㅤㅤㅤㅤㅤㅤㅤㅤㅤㅤㅤㅤㅤㅤㅤㅤㅤㅤㅤㅤㅤㅤㅤㅤㅤㅤㅤㅤㅤㅤㅤㅤㅤㅤ
ㅤㅤㅤㅤㅤㅤㅤㅤㅤㅤㅤ

ㅤㅤㅤㅤㅤㅤㅤㅤㅤ[Strawpage](https://itgtoml.straw.page)ㅤㅤ · ㅤㅤ[Carrd](https://itgtoml.carrd.co)ㅤㅤ ·ㅤㅤ [Ata](https://itgtoml.atabook.org)
ㅤㅤ

ㅤㅤㅤㅤㅤㅤread carrd before proceeding, __extremely mandatory.__


// Dropdown Menu
// https://gist.github.com/2795856
(function($) {
    "use strict";
    // Toggles .active
    $(".submenu-trigger").click(function() {
        $(".submenu-trigger").not(this).removeClass("active");
        $(this).toggleClass("active");
        return false;
    });
    $(".trigger a").click(function(e) {
        e.preventDefault();
    });
    // Prevents expanded menu item from hiding when clicking a subitem 
    $(".submenu").click(function(e) {
        e.stopPropagation();
    });
    // Hides the submenu when clicking outside the nav and
    // removes .active from selected nav items
    $(document).click(function() {
        $(".submenu").addClass("hidden");
        $(".submenu-trigger").removeClass("active");
    });
});
