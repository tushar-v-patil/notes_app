# Notes App

• The app uses Android Architecture Component (Live data, Room Database, View Model).

• MVVM Architecture is followed.

• Scalable, Robust, and Maintainable App.

• Used of Recycler view over List view.

# Flow Of the App (MVVM Architecture)

	UI Controller (Activity) 
	     \/
	ViewModel (Live Data) (data holding)
	     \/
	Repository (clean API)
	     \/
	-------------- ROOM Database (singleton class)
	     \/
	DAO (Data Access Object) (query operations)
	     | 
	SQLite [ENTITY/TABLE] (table creation)

# UI Of The App

![Screenshot (62)](https://user-images.githubusercontent.com/68781168/120649203-1fa75600-c49a-11eb-85c5-d9252a5ec7ff.png)

# Add Notes

![Screenshot (63)](https://user-images.githubusercontent.com/68781168/120649244-2b931800-c49a-11eb-869b-8574e3771cc1.png)

![Screenshot (64)](https://user-images.githubusercontent.com/68781168/120649291-3483e980-c49a-11eb-8b21-a89b7fa2325b.png)

# Delete Notes

![Screenshot (66)](https://user-images.githubusercontent.com/68781168/120650381-5c278180-c49b-11eb-8497-71c4baacac01.png)

# RecyclerView is used. (Optimization over ListView)

https://miro.medium.com/max/700/1*8go_yZFE5Gf9au_P48_qKw.png


