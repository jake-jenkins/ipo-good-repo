# TODO

## Folder Structure

/libs - would prefer to see this gone and any logic to be in the page file.

### Pages Structure

/pages
    /transaction-name
        index.tsx
        /components
            component-name.tsx
        /tests
            index.tsx
            component-name.tsx
        /page-name
            index.tsx
            /components
                component-name.tsx
            /tests
                index.tsx
                component-name.tsx

### Component Structure

/components
    /gds
        /componentA
            componentA.tsx
            test.tsx
        index.tsx // exports all components so they can be imported in single line
    /layout
        /componentA
            componentA.tsx
            test.tsx
        index.tsx // exports all components so they can be imported in single line

### Shared Services

In place of /utils

/lib
    /state
    /feature-flags
    /
