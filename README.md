# 📚 Bookstore XML Project
- `bookstore.xml` - The main XML file representing a collection of books.
- `bookstore.dtd` - DTD (Document Type Definition) file for structural validation.
- `bookstore.xsd` - XSD (XML Schema Definition) for type-based validation.
- `style.css` - CSS file used to style the XML output in browsers.

## 🛠 How to Use
1. **Open in Browser:**
   - Use a browser like chrome that supports XML and CSS rendering.
   - Open the `bookstore.xml` file. It will automatically apply styles from `style.css`.

2. **Validation:**
   - **DTD Validation:** The XML file links to `bookstore.dtd` using the `<!DOCTYPE>` declaration.
   - **XSD Validation:** The XML file also references `bookstore.xsd` using the `xsi:noNamespaceSchemaLocation` attribute.
   - Use an IDE like Visual Studio Code or online XML validators to validate the XML file against the DTD and XSD.
