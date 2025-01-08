# Songs_Recommendation_using_Word2Vec_model
A song recommendation system is made using Word2Vec model 
Song Recommendation using Word2Vec
This project leverages the Word2Vec algorithm to generate song embeddings based on human-curated playlists and artist-based similarities.

Playlist-based Recommendation: In this approach, songs are treated as "words" and playlists as "sentences." The model is trained on playlists, where songs that frequently co-occur are learned to be contextually similar. By capturing these relationships, the model generates embeddings that allow for recommending songs based on their co-occurrence in playlists, effectively reflecting user preferences.

Artist-based Recommendation: Another approach involves recommending songs based on the artist. If the name of an artist is provided, the model identifies and suggests similar songs by the same artist, helping users discover tracks that align with their favorite musicians.

Both methods utilize the power of Word2Vec embeddings to offer personalized and contextually relevant song recommendations.
