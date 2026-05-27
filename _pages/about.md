
</div>

<script>
  document.addEventListener("DOMContentLoaded", function () {
    var toggle = document.getElementById("publication-toggle");
    var additionalPublications = document.getElementById("additional-publications");

    if (!toggle || !additionalPublications) {
      return;
    }

    toggle.addEventListener("click", function () {
      var isExpanded = toggle.getAttribute("aria-expanded") === "true";

      additionalPublications.hidden = isExpanded;
      toggle.setAttribute("aria-expanded", String(!isExpanded));
      toggle.textContent = isExpanded ? "Show more publications" : "Hide additional publications";
    });
  });
</script>

# 🎖 Honors and Awards
- *2026.06* Outstanding Graduate of Beihang University (Master's).
- *2023.06* Outstanding Graduate of Beihang University (Bachelor's).

# 📖 Education
- *2026.09 - incoming*, Ph.D. student at Shanghai Jiao Tong University, jointly trained with Shanghai Artificial Intelligence Laboratory.
- *2023.09 - 2026.06*, M.S. student, School of Software, Beihang University.
- *2018.09 - 2023.06*, B.S. student, School of Software, Beihang University.
