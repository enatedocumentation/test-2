# 13. Multilingual Support

Enate supports the following languages:

1. English
2. French
3. German
4. Romanian
5. Hungarian
6. Polish
7. Spanish
8. Portuguese Brazilian
9. Russian

The Operations environment for end users to deliver the service fully supports these languages and each user will be allowed to choose their preferred language along with date-time pattern in their user profile settings.

To set a preferred language, select a language from the Language dropdown list in User Settings.

![](../.gitbook/assets/0%20%2812%29.png)

The display of labels will appear in the logged-on user’s preferred language - this is achieved by adding a ‘language package’ into **Enate**. Each language package will have mapping for user-specific language like Portuguese, for example, ‘**Queue**’ will be ‘**Fila’** and ‘**Action’** will be ‘**Açao’** in Portuguese.

Here is the list of UI elements which will be available in the logged-on user’s preferred language:

<table>
  <thead>
    <tr>
      <th style="text-align:left">Item</th>
      <th style="text-align:left">Details</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td style="text-align:left">Home Page</td>
      <td style="text-align:left">
        <ol>
          <li>RAG filters</li>
          <li>My Team</li>
          <li>Bot Farm</li>
          <li>Queue</li>
          <li>Chart</li>
          <li>Grids and column settings</li>
        </ol>
        <p>Same behaviour in Inbox page as well.</p>
      </td>
    </tr>
    <tr>
      <td style="text-align:left">Quick Find</td>
      <td style="text-align:left">People, Comms and work items search</td>
    </tr>
    <tr>
      <td style="text-align:left">Queue Page</td>
      <td style="text-align:left"></td>
    </tr>
    <tr>
      <td style="text-align:left">Navigation Links</td>
      <td style="text-align:left">Link to Builder, Queue Page or recent accessed work items etc.</td>
    </tr>
    <tr>
      <td style="text-align:left">User Profile Page</td>
      <td style="text-align:left">Here user can also change preferred language along with datetime pattern.</td>
    </tr>
    <tr>
      <td style="text-align:left">Call Handling Page</td>
      <td style="text-align:left">This page shows all communications and work items related to individual
        users</td>
    </tr>
    <tr>
      <td style="text-align:left">Work item UI</td>
      <td style="text-align:left">Labels and Button like Category picker, state etc.</td>
    </tr>
  </tbody>
</table>

{% hint style="info" %}
Note – Real names such as customer names and usernames will be remained in the original language, as entered by the configurers in Builder.
{% endhint %}

## A. Data entered by Work Manager End Users

Enate fully supports a User’s preferred language in Work Manager display and UI elements including labels, links and buttons, however anything added by you will stay in same language you originally entered it in and will not be auto-translated into any other language when being viewed by other users with a different preferred language.

For example, if a Brazilian user adds a note to a Case in Portuguese, Enate will then save the note in Portuguese in the database and will only ever show the note in Portuguese.

Here is full list of items which will be driven by user input and which **WILL NOT** be auto translated by the product:

<table>
  <thead>
    <tr>
      <th style="text-align:left">Item</th>
      <th style="text-align:left">Detail</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td style="text-align:left">Case</td>
      <td style="text-align:left">
        <ol>
          <li>Notes</li>
          <li>Emails</li>
          <li>Case - short description/title</li>
          <li>Override Action instruction o new Action launched by end user</li>
        </ol>
      </td>
    </tr>
    <tr>
      <td style="text-align:left">Action</td>
      <td style="text-align:left">
        <ol>
          <li>Notes</li>
          <li>Emails</li>
          <li>Checklist comments</li>
          <li>Action State- &apos;Unable to complete&apos; reason text</li>
          <li>Override Action Instruction of new Action launched by end user</li>
          <li>Action Peer Review note entered by reviewer</li>
        </ol>
      </td>
    </tr>
    <tr>
      <td style="text-align:left">Ticket</td>
      <td style="text-align:left">
        <ol>
          <li>Title and description of new child Tickets</li>
          <li>Name of new Action launched by user</li>
          <li>Name of new Case launched by user</li>
        </ol>
      </td>
    </tr>
    <tr>
      <td style="text-align:left">Contact</td>
      <td style="text-align:left">Details about contact like address.</td>
    </tr>
    <tr>
      <td style="text-align:left">Files</td>
      <td style="text-align:left">File name and note about file</td>
    </tr>
    <tr>
      <td style="text-align:left">Defect</td>
      <td style="text-align:left">Defect description</td>
    </tr>
    <tr>
      <td style="text-align:left">Reassignment Notes</td>
      <td style="text-align:left">Text entered by user while reassigning a piece of work to another teammate.</td>
    </tr>
  </tbody>
</table>

### Custom Data and Cards

The initial releases of multilingual functionality will not support configurers defining multiple languages when creating Custom Data and Smart Cards in Builder. Multiple cards and data items would be required for this.

### In App Notifications

The initial releases of multilingual functionality will not support notifications in languages other than English.

