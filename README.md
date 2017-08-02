# Angular-2-Router-Sample-
Angular 2 Router Sample 
import { ContactsListComponent } from './contacts-list.component';
import { ContactsDetailComponent } from './contacts-detail.component';
import { WelcomeComponent } from './welcome.component';

export const AppRoutes = [
    { 
        name: "Welcome",
        description: "Welcome to the Contacts Application.",
        path: '', 
        showInNav: true,
        component: WelcomeComponent 
    }, { 
        name: "List",
        description: "List of your contacts.",
        path: 'contacts', 
        showInNav: true,
        component: ContactsListComponent 
    }, { 
        name: "Details",
        description: "Details for your contact.",
        path: 'contact/:id', 
        showInNav: false,
        component: ContactsDetailComponent 
    }
]
