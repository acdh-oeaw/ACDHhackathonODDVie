# Judges
* Mateusz Zoltak
* Ksenia Zaytseva
# Ruling
* Asil Çetin: [vienna1946](https://github.com/asilcetin/vienna1946) [demo-app](https://asilcetin.com/projects/vienna1946/): *ex-aequo first place*
* Kevin Stadler, Ana Jeličić: [Bomb damage](https://github.com/kevinstadler/bombdamage): *ex-aequo first place*
# Reason
## Summary
We received two submissions, each focused on different objectives. Kevin focused his [Bomb damage](https://github.com/kevinstadler/bombdamage) submission on extracting information from the provided dataset whose quality is far from perfect. Asil’s [vienna1946](https://github.com/asilcetin/vienna1946) submission focused on the presentation layer by adding simple yet functional annotation features on top of the provided dataset. The nice thing is that both submissions can be seen as complementary: The better dataset being an outcome of Kevin’s work can be easily incorporated into Asil’s solution (only one additional line of code is required). Unfortunately it also makes both submissions incomparable with each other. Taking into account that both are of similar quality (details below) and we liked both of them, we apply for granting both submissions an equal first place.
## Creativity
We find both submissions creative. We much like Asil’s idea of building a community-driven service allowing to annotate a historical map and link it to external sources of information. We also find the way Kevin coupled relatively simple image transformations to extract the information from the original map creative.
## Reproducibility
Both submissions included clear installation instructions. We found no problems setting them up on our own. The data processing step of the Kevin’s submission was really well described and was also easy to reproduce.
## Reusability
In both cases reusability is limited but we do not see it as a major drawback. All in all it is only a small hackathon. Kevin’s workflow nicely demonstrates how some basic image transformations (morphological filters, color matching, etc) can be combined to extract information from a noisy raster data. While the same workflow can be applied to other maps, it will always require at least parameter tuning (more probably combining transformations in a dedicated way) and the submission does not provide any tools for finding right values. In regard to Asil’s submission, while it provides a minimal working interface allowing to add annotations, it is still more like a stub and lacks pretty many features which would be required if we wanted to reuse it as a production-ready service. And if the service is bigger, a complete code refactorization would probably be needed (see the next chapter).
## Elegance
The code of both submissions was clearly structured and easy to understand, but that is mainly due to its simplicity. The same style applied to larger software solutions would be considered messy and unclear - but again, it is only a small hackathon and not a clean and modular code challenge.
