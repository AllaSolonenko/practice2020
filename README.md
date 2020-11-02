# practice2020

# Plant App
> Multi-screen mobile application for plant care.

## Table of contents
* [General info](#general-info)
* [Screenshots](#screenshots)
* [Technologies](#technologies)
* [Setup](#setup)
* [Features](#features)
* [Status](#status)
* [Inspiration](#inspiration)
* [Contact](#contact)

## General info
The application is designed to help inexperienced gardeners. With the help of the application, they will be able to better understand the plants and how to care for them.


## Screenshots
![view of application screens](./img/screenshot.png)

## Technologies
* expo.io - SDK version 39
* Tech 2 - version 2.0
* Tech 3 - version 3.0

## Setup
Follow the link and open it on your phone using qr-code.
https://snack.expo.io/@aosolonenko/houseplants
## Code Examples
Example of usage:
` return (
      <View style={styles.container}>
        <SearchInput
          onChangeText={(term) => {
            this.searchUpdated(term);
          }}
          style={styles.searchInput}
          placeholder="Type a plant to search"
        />
        <ScrollView>
          {filteredEmails.map((plant) => {
            return (
              <TouchableOpacity
                style={styles.box}
                onPress={() => {
                  this.props.navigation.navigate('Plant', {
                    name: plant.title,
                    plant: plant,
                  });
                }}>
                <Image style={styles.img} source={{ uri: plant.imgSrc }} />
                <Text style={styles.title}> {plant.title}</Text>
              </TouchableOpacity>
            );
          })}
        </ScrollView>
      </View>
    );`

## App Screens:
- Welcome
- Login, SignUp
- Browse, 
- Plant, 


## Status
Project is: _in progress_, _finished_,



## Contact
Created by [@AllaSolonenko](https://www.flynerd.pl/) - feel free to contact me!
