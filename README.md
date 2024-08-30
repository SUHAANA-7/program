# movies.py

# Initialize an empty list to store movies
import keyword
movies_db = []

def add_movie(title ,release_year):
    movie = {
        'title': title,
        'release_year': release_year
    }
    movies_db.append(movie)

def display_movies():
    print("Movies in the database:")
    for movie in movies_db:
        print(f"{movie['title']} ({movie['release_year']}) ")

# Example usage
add_movie("Mersal", 2017)
add_movie("The Shawshank Redemption", 1994)
add_movie("Pulp Fiction", 1994)

display_movies()
