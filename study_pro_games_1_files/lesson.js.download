function handleEvents() {
    $(".clicktoshow:first").show();
    $(".clicktoshow:first").next(".solution").hide();
      
    $(".clicktoshow").click(function() {
        $(this).hide();
        $(this).next(".solution").show("slow").children(".clicktoshow:first").show().next(".solution").hide();
        return false;
    });
}

$(document).ready(handleEvents);
