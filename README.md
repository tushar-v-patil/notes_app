# Notes App

• The app uses Android Architecture Component (Live data, Room Database, View Model).

• MVVM Architecture is followed.

• Scalable, Robust, and Maintainable App.

• Used of Recycler view over List view.

# Flow Of the App (MVVM Architecture)

	UI Controller (Activity) <- displays the data and forwards the UI events
		\/
	ViewModel (Live Data) <- Holds all the data needed for UI (Concept of MVVM Architecture)
		\/
	Repository   <- Repository is a class which purpose is to provide a clean API for accessing data.
		\/
	--------- ROOM Database [Helps in accessing DAO and follows singleton pattern]
		\/
	 DAO (Data Access Object) [Query is done here on Entity]
		|
	SQLite [ENTITY/TABLE]

# UI Of The App

![Screenshot (62)](https://user-images.githubusercontent.com/68781168/120649203-1fa75600-c49a-11eb-85c5-d9252a5ec7ff.png)

# Add Notes

![Screenshot (63)](https://user-images.githubusercontent.com/68781168/120649244-2b931800-c49a-11eb-869b-8574e3771cc1.png)

![Screenshot (64)](https://user-images.githubusercontent.com/68781168/120649291-3483e980-c49a-11eb-8b21-a89b7fa2325b.png)

# Delete Notes

![Screenshot (66)](https://user-images.githubusercontent.com/68781168/120650381-5c278180-c49b-11eb-8497-71c4baacac01.png)

# RecyclerView is used. (Optimization over ListView)

https://miro.medium.com/max/700/1*8go_yZFE5Gf9au_P48_qKw.png


