# User Stories

## US-1: As a guest, I want to create an account, so that I can create my personal page

### Acceptance criteria:
- User can register using email, username, and password.
- Email and username must be unique.
- Password must contain at least 8 characters.
- Invalid registration data must be rejected with an appropriate error message.
- After successful registration, the user is redirected to the profile editing page.

## US-2: As a registered user, I want to log in to my account, so that I can access and manage my personal page
### Acceptance criteria:
- User can log in using their email or username and password.
- User is redirected to their personal page or editing interface after successful login. 
- Invalid credentials are rejected with an appropriate error message.
- Unauthenticated users cannot access protected pages.

## US-3: As an authenticated user, I want to log out of my account, so that my account remains secure when I leave the application.
### Acceptance criteria:
- User can log out using a logout button.
- User session is terminated after logout.
- User is redirected to the login page.
- User cannot access protected pages after logout without logging in again.

## US-4: As a registered user, I want to create and manage my personal page, so that I can introduce myself.
### Acceptance criteria:
- User can enter their name, description, occupation, and other personal information.
- User can upload profile picture.
- User can add social media links, skills and achievements.
- User can save their personal page
- Each personal page associated with its owner account

## US-5: As a page owner, I want to edit my personal information, so that I can keep my page up to date.
### Acceptance criteria:
- User can edit their personal information.
- User can change their profile picture.
- User can add, edit, and remove social media links, skills, and achievements.
- Changes are saved and displayed on the personal page.
- Only the page owner can edit their personal page.

## US-6: As a page owner, I want to customize the appearance of my personal page, so that it reflects my personal style.
### Acceptance criteria:
- User can change page colors and background.
- User can select available fonts.
- User can customize modules order.
- User can preview the appearance of their page.
- Customization settings are saved and applied to the public page.

## US-7: As a page owner, I want to add, remove, and rearrange modules on my personal page, so that I can organize its content according to my preferences.
### Acceptance Criteria:
- User can add available modules to their page.
- User can remove existing modules.
- User can rearrange modules.
- Changes are saved and displayed on the public page.
- Only the page owner can manage their modules.

## US-8: As a page owner, I want to share my personal page using a public link, so that other people can view it.
### Acceptance Criteria:
- Each personal page has a unique public URL.
- User can copy the public URL using a share button.
- The public URL can be opened without authentication.
- The shared link leads to the correct personal page.

## US-9: As a visitor, I want to view someone's personal page, so that I can learn more about them.
### Acceptance Criteria:
- Visitor can access a personal page using its public URL.
- Personal information and modules are displayed correctly.
- The page can be viewed without registration or login.
- Visitors cannot edit the personal page. 
- The page is displayed correctly on desktop and mobile devices.