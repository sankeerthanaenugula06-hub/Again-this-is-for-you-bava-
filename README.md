# Again-this-is-for-you-bava-
<button class="primary" onclick="goToPage(2)">Next 💕</button>
function goToPage(pageNumber) {
    document.querySelectorAll(".page").forEach(function(page) {
        page.classList.remove("active");
    });

    var nextPage = document.getElementById("page" + pageNumber);

    if (nextPage) {
        nextPage.classList.add("active");
        window.scrollTo(0, 0);
    }
}
