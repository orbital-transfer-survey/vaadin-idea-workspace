vaadin-idea-workspace
=====================

### Features available
* Compile Vaadin (hurray!)
* Compile Themes and Widgetset
* Run TB3 tests

### Missing features
* Run DevMode
* Something else probably

### Getting started
#### 1. Clone repos
````sh
git clone https://github.com/vaadin/vaadin.git
git clone https://github.com/vaadin/gwt.git
git clone https://github.com/vaadin/gwt-tools.git
````
#### 2. Build GWT
````sh
cd gwt
ant
ant elemental
cd ../vaadin
ant -f gwt-files.xml unpack.gwt
````
#### 3. Copy project files
````
https://github.com/Saulis/vaadin-idea-workspace/archive/master.zip

#### 4. Fix JUnit defaults screenshot directory


