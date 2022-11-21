# cs39aa_project_part1 Project Explanation
The data set I have chosen consists of movie reviews from Rotten Tomatoes. I gleaned the data from Kaggle then trimmed the 1 million plus observations to 10,000; there were some null observations which were also trimmed. The reviews are classified as either Rotten or Fresh, and the goal of this project will be to create a model to predict if the y observation is either Rotten or Fresh (represented in the Review_Type binary vector) with a reasonable degree of confidence. There is also a binary vector of observations denoting either a Top Critic or not a Top Critic, I will also be attempting to predict if the review was created by a Top Critic or not.
# cs39aa_project_part2 Project Explanation
The data set is the same, but now the set has been vectorized and tranformed into a one-hot encoded tensor, and run through a Random Forest model. The results were tremendous, but I will need to really dig into this dataset to assess it make sure there is a disparate amount of movies reviewed.
-----------------------------------------------------------------------------------------------------------------------------------------------------
#WHO ARE TOP CRITICS?
Top Critic is a designation created to distinguish Tomatometer-approved critics who excel at their craft. Critics selected are well-established, influential, and prolific; they are, in a sense, the cream of the crop. Top Critic status is granted by a set of criteria and a selection panel and cannot be applied for.

Reviews published by Top Critics feature in-depth analysis, supported by a breakdown of formal and thematic elements. Top Critics exhibit a deep knowledge of film/TV history, and their reviews may also provide valuable cultural context. While their reviews incorporate the lens of their own experience, they also exhibit the ability to remove any biases that may prevent them from serving the audience at-large. Overall, reviews from Top Critics are compelling, provide a sense of the viewing experience, exhibit a recognizable voice, and may influence the larger cultural conversation around a film or TV series.

Top Critics demonstrate commitment to criticism beyond reviewing and create impact in a number of ways, including but not limited to:

Maintaining a professional reputation among fellow critics and within the industry for their high-quality work, championing emerging talent in film and/or television (e.g. new filmmakers and writers), and building community both in person and through social engagement.
Investing in the next generation of criticism via mentorship, teaching, participating in panels and workshops, programming or moderating screenings, and/or publishing books on film and/or television.
Participating in the evolution of criticism via newer review formats (i.e. podcasts and video).
Peer evaluation and external expertise is also taken into consideration in selecting candidates for this designation. We have collaborated with an advisory group of critics and industry professionals chosen for their diverse backgrounds and prominence in the field in order to ensure and maintain quality for the designation.
Eligible critics are individually-approved for Rotten Tomatoes and also meet the following guidelines:

Have reviewed professionally for a minimum of five years
Critique film/TV on a regular and frequent basis, a minimum of four to six times per month
Publish reviews at outlets with a verifiable audience demonstrated by:
Consistent web traffic with at least five million visits over six months
450k followers on Twitter
500k video subscribers
For podcasts, at least 1k ratings and 4 stars on Apple Podcasts
