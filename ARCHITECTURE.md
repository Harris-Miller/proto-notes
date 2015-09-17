
Proto Notes Concept
===================


# Client

## Application

The shell of the application. Logo, login, main navigation, footer links.

#### Header

Main Logo on left, Login on right. Login becomes User Management link and display of gravatar once logged in

#### Sidebar

Main Navigation

- Projects

###### TODO


#### Body

Main Outlet of Application, Application index and all Routes render here


#### Footer

Meta Data / Link


## Project Page

1 to N levels deep Containers.

#### Containers

**Containers** represent Projects > Sub-projects > Sections > etc... (this hierarchy can be whatever)

Each **Container** belongsTo another **Container** (top level belongsTo null), and hasMany children **Containers**

**Containers** hasMany Protos, have names

Each Container Level Can *collapse*, which show/hides the contain and it's children, and *focus*, which hides the containers parent containers (except top level)

Sortable Alpha or Date Created

A **container** will have an *add proto* button

A **container** will contain a list of **Proto Links**

#### Proto Links

A **Proto Link** is a links to a **Proto's** edit page

A **Proto Link** belongsTo a **container**

Sortable Alpha or Date Created/Edited


## Proto Page

Contains **Container** breadcrum trail will links that **Container's** focused view

Displays Image in center

Right-side Action Bar that let's you add Notes and other things to Proto, at any location on the image being displayed

## Objects


# Server

## Routes

## Services


# Database

