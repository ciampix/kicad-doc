#
# Part of the KiCad ASCIIDOC Documentation Project
#
# (c)2015 KiCad Developers
# (c)2018 Heitor de Bittencourt <heitorpbittencourt@gmail.com>
# (c)2019 Mathias Neumann <alfrede@opferindustries.de>

set( PDF_GENERATOR "FOP" CACHE STRING "Specify which PDF generator to use: DBLATEX|FOP" )

add_adoc_option( -a latexmath )
KiCadDocumentation( pcb_calculator )
