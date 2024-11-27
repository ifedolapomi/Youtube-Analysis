# Youtube-Analysis

## About the Dataset
This dataset contains detailed engagement metrics for YouTube videos over time. The data includes views, likes, comments, shares, and other key metrics for individual videos, allowing for analysis of video performance and audience interaction.

## Business Questions 
1. Video Performance Analysis
- Which videos have the highest and lowest average view duration, and how do these compare in terms of likes and shares?
- How do trends in views, likes, and estimated minutes watched evolve for the top 5 performing videos over time?
- What is the correlation between average view percentage and subscriber gains for individual videos?
- Which videos show a sharp increase in daily views, and what factors (e.g., annotations, cards) contributed to this growth?
- Are videos with higher shares more likely to be added to playlists frequently?
2. Audience Interaction
- Which videos receive the highest engagement (likes, comments, shares) relative to their views?
- What is the relationship between annotation click-through rates and overall engagement metrics?
- Which videos have the highest card click rates, and how does this influence subscriber behavior?
- How do videos with higher red views and estimated red minutes watched compare in terms of audience interaction (comments, likes, shares)?
- What is the impact of dislikes on audience interaction for specific videos?

## Columns 
1. video_id: The unique identifier for each YouTube video.
2. day: The date of the video engagement data (format: YYYY-MM-DD).
3. views: The total number of views the video received on that day.
4. redViews: The number of red views (e.g., views where users interacted with specific content).
5. comments: The number of comments made on the video.
6. likes: The number of likes received on the video.
7. dislikes: The number of dislikes received on the video.
8. videosAddedToPlaylists: The number of times the video was added to playlists.
9. videosRemovedFromPlaylists: The number of times the video was removed from playlists.
10. shares: The number of times the video was shared.
11. estimatedMinutesWatched: The total estimated minutes of the video watched.
12. estimatedRedMinutesWatched: The total estimated red minutes watched (similar to views but involving specific content interactions).
13. averageViewDuration: The average duration of views for the video (in seconds).
14. averageViewPercentage: The average percentage of the video watched.
15. annotationClickThroughRate: The click-through rate for video annotations.
16. annotationCloseRate: The close rate for video annotations.
17. annotationImpressions: The number of times an annotation was shown to viewers.
18. annotationClickableImpressions: The number of times a clickable annotation was shown.
19. annotationClosableImpressions: The number of times a closable annotation was shown.
20. annotationClicks: The number of clicks on the annotations.
21. annotationCloses: The number of times the annotation was closed.
22. cardClickRate: The click-through rate for cards in the video.
23. cardTeaserClickRate: The click-through rate for teaser cards.
24. cardImpressions: The number of times a card was shown in the video.
25. cardTeaserImpressions: The number of times a teaser card was shown in the video.
26. cardClicks: The number of times a card was clicked.
26. cardTeaserClicks: The number of times a teaser card was clicked.
27. subscribersGained: The number of subscribers gained on the day due to the video.
28. subscribersLost: The number of subscribers lost on the day due to the video.
