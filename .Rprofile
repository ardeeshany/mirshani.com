# run the global .Rprofile if it exists (you may configure blogdown options
# there, too, so they apply to any blogdown projects)
if (file.exists("~/.Rprofile")) {
  base::sys.source("~/.Rprofile", envir = environment())
}

# fix Hugo version
options(blogdown.hugo.version = "0.79.0")

options(blogdown.hugo.version = "0.79.0",
        # to automatically serve the site on RStudio startup, set this option to TRUE
        blogdown.serve_site.startup = TRUE,
        # to disable knitting Rmd files on save, set this option to FALSE
        blogdown.knit.on_save = FALSE,
        blogdown.files_filter = blogdown:::md5sum_filter,
        # other nice to haves!
        blogdown.title_case = TRUE,
        blogdown.initial_files = FALSE,
        # nice defaults!
        blogdown.new_bundle = TRUE,
        blogdown.warn.future = TRUE,
        blogdown.draft.output = FALSE
)
