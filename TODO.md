# TODO List

## Performance Improvements

### File: `view.py`

- [ ] **Task**: Optimize API requests.
  - [ ] Implement asynchronous requests using `aiohttp` for improved responsiveness.
  - [ ] Explore ways to parallelize image loading and resizing operations.

- [ ] **Task**: Implement caching mechanism.
  - [ ] Integrate a caching system to avoid redundant API calls.
  - [ ] Set up cache expiration strategies for efficient memory usage.

- [ ] **Task**: Enhance error handling.
  - [ ] Implement comprehensive error handling mechanisms for better user feedback.
  - [ ] Handle network errors, API response errors, and other potential issues gracefully.

- [x] **Task**: Reduce amount of comics displayed per page.
  - [x] ~~Reduce comics displayed to 25.~~
  - [x] Tied to new feature, create multiple pages to display remaining comics.

## New Features

### File: `view.py`

- [ ] **Task**: Display additional comic details.
  - [ ] Include fields like price, release date, and genre in the displayed comic information.
  - [ ] Ensure the UI accommodates new details without clutter.

- [ ] **Task**: Implement dynamic search results layout.
  - [ ] Explore responsive UI design to adapt to different screen sizes.
  - [ ] Consider a grid-based layout for more visually appealing results.

- [x] **Task**: Add pagination support.
  - [x] Split search results into manageable pages for a better user experience.
  - [x] Include navigation controls for users to move between result pages.

- [ ] **Task**: Implement favorites list.
  - [x] Create a database schema for storing favorite items.
    - [x] Define necessary fields such as character name, comic title, and additional details.
  - [x] Integrate a database management system (e.g., SQLite) to handle favorites storage.
  - [x] Develop UI elements for users to add/remove items from the favorites list.
  - [x] Implement functionality to save user-selected characters or comics to the favorites list.
  - [x] Display the favorites list in a separate section of the UI for quick access.
  - [x] Allow users to view detailed information about items in the favorites list.
  - [ ] Implement the ability to clear the entire favorites list.
  - [x] Ensure data consistency and persistence across application sessions.

- [ ] **Task**: Implement advanced search filters.
  - [ ] Allow users to refine search results using character attributes (powers, affiliations, appearances).
  - [ ] Include filters for comic attributes (series, creators, publication dates).
  - [ ] Enable users to combine multiple filters for precise search results.

- [ ] **Task**: Implement user authentication and personalization.
  - [x] Develop user registration and login functionality.
  - [ ] Allow users to create personalized profiles and save preferences.
  - [ ] Enable bookmarking or saving of favorite characters or comics.
  - [ ] Provide personalized recommendations based on user preferences and search history.

- [ ] **Task**: Integrate comic book reading experience.
  - [ ] Implement a comic book reader within the application.
  - [ ] Allow users to view comic book pages directly in the application.
  - [ ] Include features like zoom, pan, and navigation controls for seamless reading.
  - [ ] Provide options to adjust reading settings (page layout, background color).

- [ ] **Task**: Expand character and comic details.
  - [ ] Include character biographies, origin stories, and key events.
  - [ ] Display a list of notable comic book appearances for each character.
  - [ ] Show detailed information about comic book issues (cover art, synopsis, credits).

- [ ] **Task**: Implement related content and recommendations.
  - [ ] Display related characters frequently associated with the current character.
  - [ ] Suggest similar comic books based on user's viewing history or preferences.
  - [ ] Recommend characters or comics enjoyed by users with similar interests.

- [ ] **Task**: Develop user interaction and community features.
  - [ ] Allow users to rate and review characters and comic books.
  - [ ] Implement a commenting system for discussions on characters and comics.
  - [ ] Create forums or discussion boards for user conversations about Marvel characters and storylines.
  - [ ] Enable users to create and share custom lists or collections of favorite characters or comics.

- [ ] **Task**: Integrate multimedia content.
  - [ ] Include videos (character trailers, comic book animations) to enhance user experience.
  - [ ] Display character artwork, concept art, or fan art for visual variety.
  - [ ] Incorporate audio clips (character voices, soundtrack snippets) for an immersive atmosphere.

- [ ] **Task**: Implement offline access and data persistence.
  - [ ] Allow users to view cached data when no internet connection is available.
  - [ ] Store user preferences, bookmarks, and reading progress locally for seamless experience across sessions.
  - [ ] Synchronize data between devices for a consistent experience across platforms.

- [ ] **Task**: Support internationalization and localization.
  - [ ] Implement support for multiple languages to cater to a global audience.
  - [ ] Develop localized user interfaces and content based on user's language preferences.
  - [ ] Ensure the application follows internationalization best practices for date, time, and currency formatting.

- [ ] **Task**: Implement accessibility features.
  - [ ] Provide keyboard navigation and screen reader support for visually impaired users.
  - [ ] Allow users to adjust font sizes, colors, and contrast for better readability.
  - [ ] Include alternative text for images and multimedia content to ensure accessibility.

## General Improvements

### File: `view.py`

- [ ] **Task**: Refactor code for readability and modularity.
  - [ ] Break down large functions into smaller, focused ones.
  - [ ] Improve variable naming and code comments for clarity.

- [ ] **Task**: Review and optimize image loading.
  - [ ] Investigate alternative image loading libraries or methods.
  - [ ] Optimize the resizing process for better performance.

- [ ] **Task**: Ensure consistent user interface.
  - [ ] Review and standardize UI elements for a cohesive design.
  - [ ] Check color schemes, fonts, and spacing for consistency.

- [ ] **Task**: Update API request parameters.
  - [ ] Review Marvel API documentation for the latest request parameters.
  - [ ] Ensure the application aligns with Marvel API changes.

- [ ] **Task**: Reorganize the _init_ for SearchView
  - [ ] Reorganize for readability.
  - [ ] Create gui method for more readability and modulation

- [ ] **Task**: User interface bug
  - [ ] Fix UI bug where after closing comic list window the scrollbar is not functioning.

## Additional Considerations

### File: `view.py`

- [ ] **Task**: Explore ways to manage and document `TODO` items.
  - [ ] Consider using inline comments or dedicated sections to track `TODO` items.
  - [ ] Investigate tools or practices for efficient task management within the codebase.

- [ ] **Documentation: `TODO.md`**
  - [ ] Regularly review and update the `TODO.md` file.
    - [ ] Ensure that the `TODO.md` file accurately reflects the current development priorities.
    - [ ] Keep the file organized for easy reference.

## Controller and Model Enhancements

### File: `controller.py`

- [ ] **Task**: Review and optimize the search logic.
  - [ ] Evaluate the efficiency of the current character search algorithm.
  - [ ] Explore algorithmic improvements or alternative approaches.

### File: `cache.py`

- [ ] **Task**: Consider extending caching to other modules.
  - [ ] Assess the feasibility of using caching in other parts of the application.
  - [ ] Explore opportunities to optimize data retrieval using caching.

### File: `model.py`

- [ ] **Task**: Ensure consistent use of configuration parameters.
  - [x] Review and standardize the usage of `PUBLIC_KEY` and `PRIVATE_KEY` across the application.
  - [ ] Confirm that configuration parameters are consistently applied.

## Main Application

### File: `main.py`

- [ ] **Task**: Enhance version management.
  - [ ] Investigate automated version management tools or practices.
  - [ ] Consider integrating version information into the application UI.

- [ ] **Task**: Review and improve configuration handling.
  - [ ] Assess the current configuration setup for robustness.
  - [ ] Explore options for managing user preferences and settings.

- [ ] **Task**: Investigate user preferences handling.
  - [ ] Explore methods for storing and retrieving user preferences, such as window size.
  - [ ] Consider providing users with options to customize their experience.

## Ongoing Research

- [ ] Investigate ways to further improve application performance.
- [ ] Explore additional features to enhance user experience.

## General Research

- [ ] **Task**: Explore emerging technologies and libraries.
  - [ ] Keep abreast of new developments in Python and related technologies.
  - [ ] Investigate potential libraries or frameworks for future integration.

- [ ] **Task**: Research best practices in tkinter application development.
  - [ ] Explore community guidelines and recommendations for building robust tkinter applications.
  - [ ] Research patterns for structuring large-scale tkinter projects.

- [ ] **Task**: Investigate potential security vulnerabilities.
  - [ ] Conduct a security review of the application code.
  - [ ] Stay informed about common security threats and mitigation strategies.

- [ ] **Task**: Explore potential collaboration opportunities.
  - [ ] Investigate forums, communities, or platforms where collaboration with other developers is possible.
  - [ ] Explore opportunities for code reviews or collaborative projects.

- [ ] **Task**: Research tkinter application testing methodologies.
  - [ ] Explore automated testing frameworks compatible with tkinter.
  - [ ] Investigate strategies for creating comprehensive test suites.