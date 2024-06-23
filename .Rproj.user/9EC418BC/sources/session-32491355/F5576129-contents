# Create your own theme

yan_holtz_theme <- function() {
  theme_ipsum() +
    theme(
      plot.title = element_text(color = "#69b3a2", size = 18, face = "bold"),
      axis.text.x = element_text(size = 7),
      axis.text.y = element_text(size = 7)
    )
}


ggplot(mtcars, aes(x = mpg, y = wt)) +
  geom_point() +
  labs(title = "Customized Scatterplot", x = "Miles Per Gallon", y = "Weight") +
  yan_holtz_theme()
