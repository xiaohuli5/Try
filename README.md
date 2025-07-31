# Try
```CSharp
using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;

namespace CraftTweaker_Editor.API
{
    public interface IExtend
    {
        /// <summary>
        /// Gets the name of the extension.
        /// </summary>
        string Name { get; }
        /// <summary>
        /// Gets the version of the extension.
        /// </summary>
        string Version { get; }
        /// <summary>
        /// Gets the author of the extension.
        /// </summary>
        string Author { get; }
        /// <summary>
        /// Gets a description of the extension.
        /// </summary>
        string Description { get; }
        
        /// <summary>
        /// Initializes the extension.
        /// </summary>
        void Initialize();
        /// <summary>
        /// Updates the extension.
        /// </summary>
        void Update();
    }
}
```
