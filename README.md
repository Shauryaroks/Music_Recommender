# Music Recommendation System with Django Web Interface

A hybrid recommendation system combining K-Nearest Neighbors (KNN) and K-Means clustering algorithms, integrated with a Django web interface for user interaction.

## Features
- **Dual Algorithm Approach**: Combines KNN for personalized recommendations + K-Means for genre clustering
- **Spotify Dataset**: Uses Kaggle's Spotify Tracks Dataset (900K+ tracks)
- **Web Interface**: Built with Django templates, HTML5, CSS3
- **Machine Learning Integration**: Scikit-learn for model implementation
- **Feature Analysis**: Danceability, Energy, Tempo, Valence, etc.

## Prerequisites
- Python 3.8+
- Django 4.2+
- scikit-learn 1.3+
- pandas 2.0+
- numpy 1.24+

### Recommendation System
1. **Data Preprocessing**  
   - Normalize audio features using StandardScaler
   - Handle categorical features (genre, key)

2. **K-Means Clustering**  

3. **K-Nearest Neighbors**

   ### Web Interface (Django)
1. **Views**

2. **URL Routing**

   3. **Templates**  
- Bootstrap 5 for responsive design
- Interactive search form with autocomplete

## Usage
1. Access `http://localhost:8000`
2. Search for tracks by title/artist
3. View recommendations with:
- Similar tracks (KNN)
- Genre clusters (K-Means)
4. Click tracks to play 30s previews

## Future Enhancements
- User authentication system
- Playlist generation
- Real-time listening history integration
- Advanced filtering (mood, activity)

## License
MIT License

## Acknowledgments
- Kaggle for Spotify dataset
- Scikit-learn for ML algorithms
- Django Software Foundation

